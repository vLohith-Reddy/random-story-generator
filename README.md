# random-story-genrater
import random
Sentence_starter = ['About 100 years ago','A long time ago',' A few years ago', 'Once upon a time']
character1 = [' there was a king, Vikramaditya.',' there was a emperor, Akbar.',' there was a rabbit, Dharmaraj.',' there was lion, Bahubali.']
character1_qualities=[' He was very rich and dilatory.',' He was lethargic and reserved.',' He was very intelligent and apathetic.' ]
character2_qualities = [' He has a friend, Midas. Midas is very fast and interlligent.',' He has a enemy, Ravan. Ravan is sharp and brave.','He has a daughter,Rudramadevi.Rudramadevi is a pretty and bright.']
story_plot = [ ' One day they both want to play kabaddi ,',' One day they both want to play football',' One day they both want to play kho-kho',' One day they both want to play volleyball']
place=[' in a  ground which is near to forest.', ' in a place,named natures land.',' in a palce which is near to Ganga river.']
happened=[' They both were playing very well,suddenly they started fighting with some misunderstandings',' They started playing the game,they both using there ideas and intelligent to win the game',' They started the game, But sudeenly rain is started.']
conclusion=[' After sometime , they stopped the game  and went to there houses with happiness.AND THIS IS AN HAPPY ENDING..',' After sometime,they get a call from their families , so went to the their houses, but still the game is not completed. AND THIS IS AN HAPPY ENDING....',' They played upto night, but they stopped the the game and decided to go their houses.The game is completed buut it is a draw.THE END....']
print(random.choice(Sentence_starter)+random.choice(character1)+random.choice(character1_qualities)+random.choice(character2_qualities)+random.choice(story_plot)+random.choice(place)+random.choice(happened)+random.choice(conclusion))
