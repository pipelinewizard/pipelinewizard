Week 11 of Learning Data Engineering in Public: Here’s What I Learned This Week



1. Git Commands - Rename Branch:



I renamed my local branch from 'master' to 'main' to match GitHub's default branch.



To rename your local Git branch, you can do it in two ways:

1. Rename current branch: git branch -m new_branch_name

2. Rename another branch: git branch -m old_branch_name new_branch_name



2. Git Sub Modules:



I thought consolidating all my repositories into one parent repository using Git submodules would make things simpler. I was wrong. I assumed commits made to the child repositories would automatically update in the parent repository, but that wasn’t the case. After every commit and push to a child repo, I had to manually update, commit and push in the parent repo 😔



To update a submodule in a parent repo: 'git submodule update --remote'



3. Github Profile README:



After deciding not to use submodules to organize my repos, someone on my stream suggested using a GitHub Profile README instead. GitHub has a feature where if you create a repository with the same name as your username, you can add a README that displays on your profile's homepage.



You can check mine out here: https://lnkd.in/gntYJdDR



NYC Taxicab Project Update:



I'm still in the transformation stage with the NYC Taxicab dataset. This week, I worked on creating daily, weekly, and monthly summary tables for location data (e.g., daily_summary_by_end_city, monthly_summary_by_start_borough). The goal is to avoid loading the full 14 million-row parquet table into a BI tool by optimizing the process with these summary tables.



Recap:



I was able to study and stream 5/5 days this week, making significant progress. I focused on updating systems and getting closer to the serving phase of the first iteration of the NYC taxicab pipeline. However, I didn’t get to read as much as I’d hoped. To address this, I started listening to Martin Kleppmann lectures on distributed systems on YouTube a few nights this week.



Reading & Resources:



I'm currently reading Designing Data-Intensive Applications by Martin Kelppmann, this week I read about bitmapping and run-length encoding which are techniques for compressing large tables to optimize indexing.



Next Week's Goals:



Next week, I aim to officially complete the transformation stage for the first iteration of the NYC taxicab dataset. I'm also planning to publish my first article on Substack. While I’ve been consistently posting my notes from working sessions, I think it's time to start consolidating my learning.



Just one week shy of three months of learning data engineering in public! —LET'S GO!



Have a great weekend, everyone!



Follow along with my learning journey and join me live as I work through data engineering challenges and projects. I stream every weekday morning – feel free to drop by, ask questions, and share your thoughts!



https://lnkd.in/g-gENgjc