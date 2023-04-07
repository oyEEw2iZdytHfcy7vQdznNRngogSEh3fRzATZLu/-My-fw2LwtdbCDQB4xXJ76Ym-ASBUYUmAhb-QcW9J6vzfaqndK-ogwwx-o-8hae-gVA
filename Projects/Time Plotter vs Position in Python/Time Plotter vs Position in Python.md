This is my most recent project. The problem I wanted to solve was that I was waiting in a long, multi-hour line to play a game. The current time, and my position in line is automatically written to a text file. I used python to grab this time and position data, and use it to predict when I would reach position 0 in line, thus finally starting to play the game. I know, this is very much overkill to play a game. However, I knew it would be more efficient if I could automate this process. 

The program would plot time vs. position, then make a trendline and see where the intercept hits position 0. Now, plotting in python is slower than just doing the math, so I started by plotting as a proof of concept, then just did the math to optimize. After this, I set up emailing via python so it could update me on my position, even if I am away from my computer. For example, when I reach position 100 in line (often I’ll start at 300) I will get an email telling me what time to expect to start playing. After tweaking the math, on April 6th, I got an email saying I’d reach position 0 at 10:22pm. Then, at 10:28pm, 6 minutes after the estimate, I reached position 0. It works so much better than I could have imagined.  