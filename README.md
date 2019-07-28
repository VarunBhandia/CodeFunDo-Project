CodeFunDo-Project
-------
### Idea:-
We will create a **Dapp** on top of hyperledger fabric where each voter will be a participant. When each participant will vote they will create a transaction. The catch is they will all be telling their preferred leader's name while creating that transaction.  One participant will only be able to make only one transaction(to avoid multiple voting). At the time of vote counting we will see the value of ***preferred leader*** on that transaction. we will use **kafka**  consensus so that leader with majority votes win.
