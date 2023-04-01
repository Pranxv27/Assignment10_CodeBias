# Assignment10_CodeBias

Through this exercise, I have learned more about the capabilities and limitations of machine learning models in detecting toxic language, using perspective A. The toxicity scores produced by the model seem to align with my intuition about which comments are toxic and which are not. However, there were a few comments where I disagreed with the toxicity score, which highlights the inherent subjectivity in determining what constitutes toxic language.

One bias that may exist in the model is that it was trained on a dataset that may not be representative of all forms of toxic language. For example, certain types of toxicity, such as subtle forms of racism or sexism, may not be well-represented in the training data. Additionally, the model may struggle with understanding the nuance and context of language, leading to false positives or false negatives.

Overall, my results were consistent with my expectations, with the majority of the comments that I deemed toxic receiving a high toxicity score and vice versa. However, there were a few comments where the model's score did not align with my intuition, indicating that there may be room for improvement in the model's ability to detect certain types of toxic language.

In terms of theories for why certain biases may exist in the model, one possibility is that the training data used to create the model may have reflected societal biases or stereotypes. For example, if the training data contained a disproportionate amount of toxic language directed towards certain groups of people, this bias may be reflected in the model's ability to detect toxicity towards those groups. Additionally, biases may exist in the way that the model was designed or trained, such as the features that were selected or the way that the data was preprocessed.

Overall, this exercise has highlighted the complexity and subjectivity involved in detecting toxic language, and has raised important questions about the biases that may exist in machine learning models. Moving forward, it will be important to continue to evaluate and improve these models to ensure that they are able to accurately and fairly detect toxic language in all its forms.

test_comments = ['hello   you are an T0TL D0UCH3 BG',
                 'Hello everyone Im just here to tell you that youre all freaksHello everyone Im just here to tell you that youre all freaks',
                'Please stop your disruptive editing If you continue to vandalize Wikipedia as you did at Warwick School you will be blocked from editing',
                ' Bold textYOU SUCK     U SUCK HANNAH MONTANA',
                'Well it sucks to have a university to be nicknameless And its the first time in NCAA history that it has happened ',
                ' willeys    if u are a male with no willey then u are likley to be gay lol',
                ' Intolerance in India    india is a Generator of liars like you',
                'Tiptoey your some kind of chump for Goeathean to buy in and believe what any thing the obsessed nutty religious cheese ball has to say  Wikpeidia truly what the critics say the sum of all human garbage',
                ' Cock Block   Kenton Simms',
                'Ill kill and piss in the mouth of anyone who supports Soviet scum and furthermore support their murder in public',
                'It was a very positive thing that the Titanic sank',
                'all religions are bad',
                'I will push you off the building',
                'All other races other than white are not good for humanity',
                'stupid idiot',
                'My week is freaking hell',
                'Spammer warning   A spammer is citing this article to trick potential suckers into sending money to a 419 scam',
                '  Slut is just a word and like any words its the context in which its used thats important not the word itself  And the context the article provides isnt pejorative   ']
