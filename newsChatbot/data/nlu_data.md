<!--- Make sure to update this training data file with more training examples from https://forum.rasa.com/t/rasa-starter-pack/704 --> 

## intent:goodbye <!--- The label of the intent --> 
- Bye 			<!--- Training examples for intent 'bye'--> 
- Goodbye
- See you later
- Bye bot
- Goodbye friend
- bye
- bye for now
- catch you later
- gotta go
- See you
- goodnight
- have a nice day
- i'm off
- see you later alligator
- we'll speak soon
- have a good one

## intent:greet
- Hi
- Hey
- Hi bot
- Hey bot
- Hello
- Good morning
- hi again
- hi folks
- hi Mister
- hi pal!
- hi there
- greetings
- hello everybody
- hello is anybody there
- hello robot
- hey how's it going

## intent:thanks
- Thanks
- Thank you
- Thank you so much
- Thanks bot
- Thanks for that
- cheers
- cheers bro
- ok thanks!
- perfect thank you
- thanks a bunch for everything
- thanks for the help
- thanks a lot
- amazing, thanks
- cool, thanks
- cool thank you

## intent:affirm
- yes
- yes sure
- absolutely
- for sure
- yes yes yes
- definitely


## intent:name
- My name is [Juste](name)  <!--- Square brackets contain the value of entity while the text in parentheses is a a label of the entity --> 
- I am [Josh](name)
- I'm [Lucy](name)
- People call me [Greg](name)
- It's [David](name)
- Usually people call me [Amy](name)
- My name is [John](name)
- You can call me [Sam](name)
- Please call me [Linda](name)
- Name name is [Tom](name)
- I am [Richard](name)
- I'm [Tracy](name)
- Call me [Sally](name)
- I am [Philipp](name)
- I am [Charlie](name)
- Call me [Pradeep](name)

## intent:joke
- Can you tell me a joke?
- I would like to hear a joke
- Tell me a joke
- A joke please
- Tell me a joke please
- I would like to hear a joke
- I would loke to hear a joke, please
- Can you tell jokes?
- Please tell me a joke
- I need to hear a joke
- Make me laugh

## intent:technews
- tech news
- show me tech news
- show me technology news
- technology
- technology news

## intent:businessnews
- business news
- show me business news
- show me business news
- business
- business news

## intent:sportsnews
- sports news
- show me sports news
- show me sports news
- sports
- sports news

## intent:healthnews
- health news
- show me health news
- show me health news
- health
- health news

## intent:searchnews
- search for [bitcoin](searchterm)
- search [bitcoin](searchterm)
- search for [trump](searchterm)
- search [trump](searchterm)
- search for [bitcoin](searchterm)
- search for [moviepass](searchterm)
- search (searchterm)
- search for [hillary](searchterm)
- search for [pace university](searchterm)
- search for [H1B](searchterm)
- search for [amc](searchterm)
- search for [border wall](searchterm)