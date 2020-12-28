# Transformer PyTorch
 Implementation of [Attention Is All You Need](https://arxiv.org/abs/1706.03762)<br>
 by Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser, Illia Polosukhin.<br><br>
 
 Used for language translation on a small german-english dataset with 230.000 sentences and mean 8 tokens per sentence.

# Training
Model size: 17 Mio. parameters<br>
batch time: 221ms<br><br>
layers: 6<br>
heads: 8<br>
batch size: 128<br>
embedding size: 300<br>
feed forward size: 2048<br><br>

![loss](https://github.com/Hauf3n/Transformer-PyTorch/blob/main/media/loss.png)

# Results
Training sentences:<br>
```
In: Ich habe dich einst gewarnt, aber du hast nicht hören wollen. | Out: I warned you once , but you did n't listen . 
In: Ich freue mich, dass ausnahmsweise mal jemand meiner Meinung ist. | Out: I 'm glad someone agrees with me for once . 
In: Ich kann dir das Geld, das du mir geliehen hast, nicht zurückzahlen. | Out: I ca n't pay you back the money you lent me . 
In: Das Essen war schrecklich, aber ich habe mich nicht beklagt. | Out: The food was terrible , but I did not complain . 
In: Diese Behauptungen entbehren einer wissenschaftlichen Grundlage. | Out: There is no scientific basis for these claims . 
In: Was hältst du davon, wenn wir heute Abend zur Abwechslung mal draußen essen? | Out: How about eating out this evening for a change ? 
In: Ich habe von ihm gehört, aber ich kenne ihn nicht persönlich. | Out: I know of him , but I do n't know him personally . 
In: Ich glaube, wir haben uns den Falschen für die Stelle gesucht. | Out: I think we picked the wrong person for the job . 
In: Ich möchte glauben, dass wir aus unseren Fehlern lernen. | Out: I 'd like to believe we learn from our mistakes . 
In: In Kalifornien haben die meisten Häuser einen Rohbau aus Holz. | Out: In California , most houses have frames of wood . 
In: Die Preise sind doppelt so hoch wie vor zehn Jahren | Out: Prices are double what they were ten years ago . 
```

My test sentences (not in dataset):<br>
```
In: Ich bin doppelt so alt wie vor zehn Jahren. | Out: I 'm double what I was ten years ago . 
In: Ich bin sehr begeistert von deinem Talent. | Out: I 'm very impressed with your talented . 
In: Das ist ein Problem, das wir lösen können. | Out: That 's a problem we can solve . 
In: Sie genießen den sanften Wind am Meer. | Out: They enjoy the ideal wind near the sea . 
In: Das ist wirklich das beste Eis der Stadt. | Out: This is really the best ice cream in town . 
In: Wie viele Menschen gibt es auf der Welt? | Out: How many people are there in the world ? 
In: Mir fällt kein neuer Satz ein. | Out: I ca n't think of a new sentence . 
In: Mein neues Modell ist ganz gut, obwohl es Schwierigkeiten gab. | Out: My new model is quite well even though it was have in trouble . 
In: Dieses Weihnachten ist wie kein anderes zuvor. | Out: This Christmas is not just one . 
In: Wie viele Häuser stehen auf der anderen Straßenseite? | Out: How many houses do are across the street ? 
In: Morgen ist schon wieder Montag. | Out: Tomorrow is already Monday . 
In: Das Fahrrad hat zwei Räder und eine Klingel und ist schnell. | Out: The bicycle has two wheels and a bell and soon fast . 
In: Augen auf, sonst fällst du auf den Boden! | Out: Watch up , next will get on the floor . 
In: Die Polizei verhaftet den Verbrecher und setzt ihn in das Auto. | Out: The police arrested the criminal and put him in the car . 
In: Ich habe zu wenig Sätze zum Trainieren des Modells. | Out: I 've some little sentences to exercise of the model . 
In: Lasst die Frau auf dem Auto tanzen. | Out: Let the wife dance in the car . 
In: Es gibt so viele Möglichkeiten, aber ich bin nicht kreativ genug. | Out: There are so many of possibilities , but I do n't think . 
In: Die Küche muss renoviert werden, sagte sie. | Out: The kitchen needs to be fixed , she said . 
In: Bitte, mach mir das Leben nicht schwer. | Out: Please do n't make me difficult for life . 
In: Heute muss ich zum Zahnarzt, obwohl es Sonntag ist. | Out: I have to go to see the dentist even much Sunday . 
In: Wie viele Einheiten bilden ein Dutzend? | Out: How many rooms do make a dozen ? 
In: Was für einen Stift braucht man für das Dokument? | Out: What kind of pen does you need for the document ? 
In: Hände hoch, oder die Hose runter. | Out: Put up , or pants down . 
```

# Conclusion
Train on a larger and richer dataset!
