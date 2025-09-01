# Translator
This is my custom translator that uses Google Translate to translate stuff 100 times.

The main reason why I made this is because (like said in Info) most of these tools are weird .exes or python scripts that barely work. I've been researching Google Translate stuff for quite some time and I've made things like this, but they were slow, and most tools are.

This tool is actually decently fast, the old tool I used to use was HyperTranslate, which **was** very fast, 100 translations in 16 seconds, before it became extremely slow and took 3+ minutes for 100 translations. I hope you enjoy this tool, as I find it quite fun to mess around with.

# Info
This isn't made with python or some sketchy .exe, it's not hard to use and very straight forward.

The difference between Full and Speed Mode is obviously one is faster than the other, but it uses less languages. Full mode uses most if not every language, while Speed mode uses the top 15 languages.

The more languages you use, the more time it takes for a translation, and it also becomes slower depending on how long your text is.

If you'd like to check what it has been translated into, open Inspect, and go into network.

Difference between legacy and new? The difference is one (legacy) makes some decent amount of sense, while the other (new) is basically schizophrenic. The results are so bad, 9/10 you're gonna get something like "And then the jjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjJJJJJJJJJJJJJJ."

Yes, this is kinda funny, although I personally use Legacy Speed, as it's fast, makes sense, but still weird.

# Bookmarklets
Before I even explain what these do, you need to know how to even install these, it's very simple, just make a bookmark and instead of a URL, put that script in.

Now, what do they do? There are currently 3 versions, lite, heavy, and highlight. All of these versions use **Legacy Speed**.

Lite is a version that doesn't send many requests very fast, it goes through every text element (top to bottom) and translates them 100 times one by one.

Heavy is a version that sends many requests, it takes the first 50 text elements and runs them through Google Translate 100 times. This is extremely fast but will slow your browser down a lot. I recommend just letting it sit while you do something else not on your browser.

Highlight is a version that will take whatever text you have highlighted, translate it 100 times, then replaces the text with the output of all the translations. I personally like this one the most as get gives you a lot of control and it doesn't slow anything down.

# Todo

- [x] Add seeds 
- [x] Add legacy and new versions (currently on legacy) 
- [x] Make new version not translate from one language to english, to another language, to english, etc... 
- [x] Make bookmarklet version

# https://0alter0.github.io/translator
