Layout
post

Title
Building a Diabetes Prediction System: My Database Systems Project

Date
2026-06-25

Categories
portfolio,university

Tags
computer engineering,database systems,DBS,machine learning,university life,UET Lahore

Image:
/assets/dbs-thumbnail.png


If the online classes were the part of this semester that tested my patience, the Database Systems project was the part that tested everything else — my teamwork, my ability to actually apply what we had been taught in lectures, and honestly my understanding of how a database and a machine learning model are supposed to talk to each other in a real application instead of just existing as two separate things in two separate notebooks.

For our final project, our group decided to build a diabetes prediction system — something that takes health-related data and predicts whether a person is likely to have diabetes based on patterns learned from existing records.

Choosing the Right Dataset
The first decision we had to make as a group was where the data would even come from. We ended up using a WHO global health dataset related to diabetes, partly because it felt like working with something that had actual real-world weight to it rather than a toy dataset made up for a classroom exercise, and partly because global health data tends to be fairly well structured, which made it easier to design a database schema around it.

Looking back, I think that choice shaped a lot of what came next — because once you are working with real health-related data, even at a student project level, you start thinking more carefully about how the data should be organized, validated, and stored, instead of just dumping everything into a single table and calling it a day.

The Database Design Half
That is really where the "database" half of the project came alive for me. Up until this point, database systems had mostly been theory in my head: normalization, primary keys, foreign keys, relationships — all things we had learned and practiced in smaller exercises. This project was the first time I actually felt the weight of those decisions.

We had to sit down as a group and figure out how to structure the data properly: what should be its own table, how patient records should relate to the health attributes being measured, and how to keep the structure clean enough that querying it later would not become a nightmare.

It is one thing to memorize what normalization is for an exam. It is a completely different thing to be staring at a messy global dataset and realizing that if you do not normalize it properly now, you are going to regret it later.

The Prediction Half
The second half of the project — the prediction part — is where things shifted from database design to something closer to applied machine learning, and that combination is honestly what made the project interesting rather than just another assignment.

Once the data was sitting in a properly structured database, we had to pull it out, clean it up, and feed it into a model that could actually learn patterns from it and make a prediction on new, unseen data. Watching the two pieces connect — the structured backend on one side and the prediction logic on the other — made the whole "database systems" course click in a way that lectures alone had not quite managed to do.

It stopped being an abstract subject about tables and joins and started feeling like the backbone of an actual working system.

A Group Project That Actually Worked
What made this project genuinely enjoyable rather than stressful was that it came together smoothly as a group. I know that is not always the case with group projects, and I have heard enough stories from classmates about mismatched schedules and uneven workloads to know we got a bit lucky here.

Everyone showed up, contributed their part, and we managed to move from a rough idea to a working system without the usual last-minute scrambling that group work tends to produce. The key was agreeing early on how the work would be split — roughly between database design and structuring on one side, and the prediction model on the other — so that nobody was stepping on anyone else's part.

The Bigger Takeaway
Thinking about it now, this project sits at an interesting intersection for me as a Computer Engineering student. It was not purely a database assignment, and it was not purely a machine learning assignment either — it was a reminder that in most real systems, these things do not exist in isolation.

A prediction model is only as good as the data feeding into it, and that data has to live somewhere, structured in a way that makes it usable rather than just stored. Our diabetes prediction project forced our group to think about both sides of that equation at once, and that combination is probably the most useful thing I am taking away from this course — more than any single lecture on normal forms or SQL syntax could have given me on its own.
