# Hey it's Paul

I'm a computer science student at the University of San Francisco. My projects range from tools for coding together to apps for collecting and working with wearable data.

I work in **Python, Java, C, and assembly**. My web and mobile projects also use JavaScript/TypeScript and Swift.

## Forklane

I built [Forklane](https://forklane.ai) with [Akshay](https://github.com/akshaylakkur). It gives collaborators a shared project space where each person can use their own AI coding agent, with automated version control. We've used it at several hackathons, including the QBI UCSF hackathon.

Behind the shared workspace is a Node.js/Express API that manages projects and sessions, a PostgreSQL database, and AWS EC2 instances for running collaborative sessions. The agent tooling also handles remote execution over SSH and syncing files between local and remote environments.

## BehaviorTrace & Apple BehaviorTrace

[BehaviorTrace](https://github.com/geddie212/BehaviorTrace) lets study participants label states such as feeling stressed or focused while wearing an EmotiBit. It brings those labels together with wearable signals, with Python workflows for processing the data and training models.

[Apple BehaviorTrace](https://github.com/geddie212/AppleBehaviorTrace) takes the data-collection side to iPhone and Apple Watch. It pairs timestamped labels with HealthKit samples and uses Supabase APIs for authentication and storing study data in Postgres. Labels are saved locally first and synced in the background, so collection can continue when the connection drops. It's a research prototype.

## Health Agent

An iOS app for logging meals and workouts through text, voice, or photos, alongside Apple Health data. The backend uses Python/FastAPI and LLM integrations, including OpenAI API calls.

The project also uses AWS Cognito for authentication, RDS/Postgres for records, S3 for uploads, and SQS for background jobs. Calculations such as calorie totals and trends are handled separately from the conversational agent.

## Other things you'll find here

Earlier Python projects include a [Flask café API](https://github.com/geddie212/cafe_api) that serves JSON from a SQLite database. There are also [Java sorting algorithms](https://github.com/geddie212/sort_algorithms) and [data structures and algorithm practice](https://github.com/geddie212/neetcode-submissions).

I use Git/GitHub for VC and Claude and Codex for AI help.

Based in SF.
