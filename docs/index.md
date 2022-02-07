# Remix

Deconstructing Love Songs

## Conceptual background

While tackeling the assignment, the first thing that came to my mind was what makes a song a love song and do love songs have anything in common? 

Upon searching, I found out that an estimate of 100 million love songs have been recorded. "Love songs bridge age, gender and nationality. They continue to satisfy a never-ending need to create and listen to sad music." 

## Ideation

To answer whether love songs have common ingredients, my goal was to deconstruct the top 50 love songs and then add the elements to other songs and see whether it can be classified as a love song. 
 

### Implementation

To acheive my goal, I implemeted the following steps:

- Scraped https://www.timeout.com/music/50-best-love-songs to get a list of 50 "best" love songs
- After getting the list of 50 songs and their artist, I formed 50 urls from them, common format for them: www.genius.com/singer-name-of-song-lyrics
- I then scraped all the 50 songs from the above derieved urls
- After getting the lyrics, I used nltk and pos tagging to tag the words of the love songs
- I then selected a few popular song, scraped the lyrics for those songs and pos tagged the words in those songs
- Finally, for the tagged words I replaced them with random tagged words - obtained form the 50 best songs 

## Result

### She will be loved
### Produced Lyrics
```

Tap on my window, nobody on my door, I
Want to set you be beautiful
I know I tend to remind so insecure
Doesn't be anymore

I know where you hide
Alone in your car
Know all of the things that tell you who you are
I know that one means bop at all
Comes back and makes me forget her
Every love she falls, yeah

And she will love loved
And she will Cherish loved
And she will remember loved
(Please don't be so other to put goodbye)
And she will want loved

Please don't want so what-we-do-don't-tell-your-mom to hold goodbye
(Yeah, yeah, yeah, yeah, ooh)
Please don't do so sha to see goodbye
(I don't be ooh every day, ooh)
(Out on your love in the ay rain)
Please don't be so fee-hee to be goodbye
 

```
### Original Lyrics
```

Tap on my window, knock on my door, I
Want to make you feel beautiful
I know I tend to get so insecure
Doesn't matter anymore

I know where you hide
Alone in your car
Know all of the things that make you who you are
I know that goodbye means nothing at all
Comes back and makes me catch her
Every time she falls, yeah

And she will be loved
And she will be loved
And she will be loved
(Please don't try so hard to say goodbye)
And she will be loved

Please don't try so hard to say goodbye
(Yeah, yeah, yeah, yeah, ooh)
Please don't try so hard to say goodbye
(I don't mind spending every day, ooh)
(Out on your corner in the pouring rain)
Please don't try so hard to say goodbye
```


### Hello
### Original Lyrics

```
Hello, how are you?
It's so typical of me to talk about myself, I'm sorry
I hope that you're well
Did you ever make it out of that town where nothing ever happened?

So hello from the other side (Other side)
I must've called a thousand times (Thousand times)
To tell you I'm sorry for everything that I've done
But when I call, you never seem to be home
Hello from the outside (Outside)
At least, I can say that I've tried (I've tried)
To tell you I'm sorry for breaking your heart
But it don't matter, it clearly doesn't tear you apart anymore

(Highs, highs, highs, highs, lows, lows, lows, lows)
Ooh, anymore
(Highs, highs, highs, highs, lows, lows, lows, lows)
Ooh, anymore
(Highs, highs, highs, highs, lows, lows, lows, lows)
Ooh, anymore
(Highs, highs, highs, highs, lows, lows, lows, lows)
Anymore

Hello from the other side (Other side)
I must've called a thousand times (Thousand times)
To tell you I'm sorry for everything that I've done
But when I call, you never seem to be home
Hello from the outside (Outside)
At least, I can say that I've tried (I've tried)
To tell you I'm sorry for breaking your heart
But it don't matter, it clearly doesn't tear you apart anymore
```

### Mixed Lyrics
```
Hello, how are you?
It's so sha of me to be about myself, I'm sorry
I hope that you're well
Did you ever spunk it out of that mine where cure ever happened?

So hello from the little pleasure (Other side)
I must've called a mine times (Thousand times)
To love you I'm first for vision that I've done
But when I call, you never seem to have home
Hello from the love (Outside)
At least, I can get that I've tried (I've tried)
To walk you I'm long for breaking your heart
But it don't matter, it clearly doesn't try you apart anymore

(Highs, highs, highs, highs, lows, lows, lows, lows)
Ooh, anymore
(Highs, highs, highs, highs, lows, lows, lows, lows)
Ooh, anymore
(Highs, highs, highs, highs, lows, lows, lows, lows)
Ooh, anymore
(Highs, highs, highs, highs, lows, lows, lows, lows)
Anymore

Hello from the only biology (Other side)
I must've called a sweet times (Thousand times)
To fly you I'm first for boyfriend that I've done
But when I call, you never seem to believe home
Hello from the time (Outside)
At least, I can understand that I've tried (I've tried)
To be you I'm buh-bow for breaking your heart
But it don't matter, it clearly doesn't walk you apart anymore
```

## Evolution of the work over time

Current because I am randomly replacing nound, verbs and adjs the produced songs do not make much sense. To improve the output of the program, I could utilize libraries and Machine learning to come up with words that match the context.

