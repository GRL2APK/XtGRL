# XtGRL
Extended textual Goal-oriented Requirements Language is the extended edition of tGRL that is a domain specific language defined over DSL grammar in Xtext. Xtext is an open source Eclipse plugin. We have extended (also reduced) the tGRL grammar to enable only those features that allow enterprise architects to specify only the functional requirements and the corresponding non-functional requirements that are desired to be satisficed.
Extensions in the Grammar are described as follows.\
**1)** It also has the notion of a *_Softgoal_* that allows enterprise architects to only specify high level NFRs that
influence certain functional requirements.\
**2)** Notion of *_Operationalization softgoals_* and *_Clain softgoals_* are introduced that are used to specify NFR catalogs.\
**3)** This extension allows the architect to specify the goal, task or resource that demands a certain specific softgoal. This requirement is represented by using new notation *_demands_*.

   ![](https://github.com/GRL2APK/XtGRL/blob/master/images/img1.PNG)
      
