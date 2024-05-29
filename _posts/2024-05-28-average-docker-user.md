## Doctor Docker &rarr; Quack Docker &rarr; Your Average Docker User

The first time I used Docker was for my [coding bootcamp](https://web.archive.org/web/20211208161720/https://www.learnhowtoprogram.com/ruby-and-rails/getting-started-with-ruby/faq-should-i-install-ruby-or-use-docker), circa 2021. To start my appreciation over this almighty software, I took on the arduous path of using Docker to work with Ruby on Rails instead running it on my machine with [chruby](https://github.com/postmodern/chruby). 

Over time, I self-patronisingly coined myself as the "Doctor Docker".

Why? 

Well, first, because I graduated pharmacy school and was so far removed from the actual profession that the only redeeming quality from completing my Doctor of Pharmacy degree was the cheeky opportunity to use "_Doctor_" title in this context. And second, because I felt a sense of purpose in helping troubleshoot my peers' Docker environment and getting them up and running. 

In actuality, all I did was google the error message and scour the results to see which fix would work well _on my computer_,[^1] while then subsequently suggest in our bootcamp's discord my found solution. You can probably see the analogy where I'm like a quack doctor who only treats the symptoms, but never addressing the root cause of the problem.

Regardless — did I help my peers and bring them up to speed with me? **_Yes_** 

Was I a quack in my understanding with Docker — AKA, a quack _docker_? **_Maybe_**

Did I truly learn how to work with Docker? **_No_**

I let the knowledge gap persist all these years after until this past month, where I decidedly sat down to learn Docker. I was motivated to run a [local environment of someone's disease predictor website](https://github.com/shiroyasha9/PredictIt) and compare the results of my AI-powered symptom checker with theirs. After some hair pulling and banging my head multiple times from frustration, I finally had the [configurations](https://github.com/davelindqvist/docker_config_predictit) figured out to get the app locally running!

But I know I only scratched the surface for what Docker could do. I found and watched Adrian Cantrill's deeper dive on [the fundamentals of Docker](https://github.com/acantril/docker-fundamentals), which I **HIGHLY** recommend to get yourself situated if you're lost about what Docker can do for you.[^2] Once you complete that, I have a good feeling you'll know your way around building, composing, and creating Docker containers, and then inevitably become another Docker user like me!

Cheers,

Your Average Docker User Dave

---

Footnotes:

[^1]: Oh, the irony.

[^2]: If there's any takeaway about Docker, try to understand that Docker allows you to ["ship the computer"](https://www.youtube.com/watch?v=5aUB1lK6jyc&list=PLTk5ZYSbd9Mg51szw21_75Hs1xUpGObDm&index=4) and prevents the frustrating case of "well, it worked on my computer machine" situation. 
