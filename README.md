Data Overview

This ETL pipeline extracts, transforms, and loads structured metadata from GitHub. The schema organizes repository activity into the following core entities:

Repositories: Core metadata including repository name, visibility, stargazers, forks, primary programming language, creation date, and license.

Commits: Event history, commit hashes, author and committer details, commit messages, and file change timestamps.

Pull Requests: PR titles, state (open, closed, merged), author details, reviewer comments, source/target branches, and time-to-merge metrics.

Issues: Bug and feature tracking data including state, labels, assignees, body content, and comment threads.

Contributors & Users: Profile metadata, contribution counts, and activity frequencies across the project.

Workflows & Actions: CI/CD pipeline execution logs, run status (success/failure), duration, and trigger events.