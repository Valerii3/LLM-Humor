# LLM-Humor
I implemented various joke-writing strategies, primarily sourced from the [Creative StandUp](https://creativestandup.com/wp-content/uploads/manual/joke-structure-guide.pdf). For each category, I generated 3 jokes. Delivering a joke can be challenging, particularly in a stand-up setting rather than during a conversation. So, most of the time LLM tried to make a straightforward joke format— posing a question followed by a humorous answer.

I utilized *GPT4o* for generating and evaluating jokes. In my opinion, the best jokes are:

```
Three sysadmins walk into a server room. The first one says, "I just patched the kernel and everything's running smoothly."
The second one says, "I just optimized the database, and the queries are lightning-fast."
The third one says, "I just ran 'rm -rf /' and—hey, where did everyone go?"
```
```
So, last weekend, my friend tells me he’s got this old laptop that’s just gathering dust and he wants to revive it.
I suggest, “Why not install a lightweight Linux distro? It’ll breathe new life into that ancient machine!”
He agrees, so I head over to help him out. We spend the whole afternoon setting it up. We partition the drive,
install Xubuntu, configure the settings, and finally, it’s running smoothly.
He’s super excited and says, “Wow, this is amazing! It feels like a brand-new laptop!”
Just as I’m feeling pretty proud of our work, he scratches his head and asks, “So, when do we install Windows 98?”
```
These jokes employ more complex techniques, such as *Broken assumptions* and the *Rule of Three*. Detailed descriptions of these can be found in the notebook.

Additionally, I aimed to automate the joke ratings using the LLM, creating a prompt similar to that found in the paper, [Is GPT-4 Good Enough to Evaluate Jokes](https://computationalcreativity.net/iccc23/papers/ICCC-2023_paper_89.pdf). It rated each joke from 1 to 5. In my case, all jokes got rating between 2-3.

### Materials
During the experiments, I read the following materials:
1) [How to Evaluate a Joke in 10 Questions](https://sceneshop.medium.com/how-to-evaluate-a-joke-in-10-questions-8502265b7504)
2) [Humorous English : a guide to comic usage, jocular speech and writing, and witty grammar](https://cir.nii.ac.jp/crid/1130282272340642944) - this one will be useful for further research.
3) [Joke Strategies In American Situational Comedy “How I Met Your Mother](https://arbitrer.fib.unand.ac.id/index.php/arbitrer/article/view/75/62) - another collection of joke strategies.
 
