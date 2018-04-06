# Drools-KIE-XLS
Business Rules Management

Drools with KIE and Decision Table

********------Drools-------************

Bullets:

1. Data Model: The data model in which rules applies. Nothing but java classes
2. Rules LHS are constraints on data model(class name & attributes)
3. Rules RHS are facts, which are in working memory
4. When we want apply rule on data, instantiate a java class and give it to rule engine. This instance is called a Fact object.
5. To work with rule engine, we have to instantiate KieContainer
6. When working with drools, have to get a KieSession from the KieContainer. This KieSession will allow you to give facts to the
rule engine and ask to fire rules.


Installing Drools Tooling:

1. JVM 7/8
2. Eclipse IDE
3. Drools runtime and tools 
