# Creating blog posts

The Knative blog is owned by the [DUX working group](https://knative.dev/community/contributing/working-groups/working-groups/#documentation--user-experience).

This section covers documentation, processes, and roles for the [Knative blog](https://knative.dev/blog/).

## Leadership

- **Technical Editors:** [Lionel Villard](https://github.com/lionelvillard), [Evan Anderson](https://github.com/evankanderson)
- **Copy Editors:** [Ashleigh Brennan](https://github.com/abrennan89), [Caroline Lee](https://github.com/carieshmarie), [María Cruz](https://github.com/macruzbar)
- **Blog Community Managers:**  [María Cruz](https://github.com/macruzbar), [Jonatas Baldin](https://github.com/jonatasbaldin)

## Contact

- Slack: [#docs](https://knative.slack.com/archives/C9CV04DNJ)

## Submit a Post

Anyone can write a blog post and submit it for review. Commercial content is not allowed. Please refer to the [blog guidelines](#blog-guidelines) for more guidance.

To submit a blog post:

1. [Sign the Contributor License Agreements](https://github.com/knative/community/blob/main/CONTRIBUTING.md#contributor-license-agreements) if you have not yet done so.
1. Familiarize yourself with the Markdown format for existing blog posts in the [docs repository](https://github.com/knative/docs/tree/main/blog). Blog posts are categorized into different directories. You can explore the directories to find examples.
1. Write your blog post in a text editor of your choice.
1. (Optional) If you need help with markdown, check out [StakEdit](https://stackedit.io/app#) or read [GitHub's formatting syntax](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax) for more information.
1. Choose a directory in the [docs repository](https://github.com/knative/docs/tree/main/blog), and click **Create new file**.
1. Paste your content into the editor and save it. Name the file in the following way: *[BLOG] Your proposed title* , but don’t put the date in the file name. The blog reviewers will work with you on the final file name, and the date on which the blog will be published.
1. When you save the file, GitHub will walk you through the pull request (PR) process.
1. A reviewer is assigned to all pull requests automatically. The reviewer checks your submission, and works with you on feedback and final details. When the pull request is approved, the blog will be scheduled for publication.
1. Ping editorial team members on Slack [#docs](https://knative.slack.com/archives/C9CV04DNJ) channel with a link to your recently created PR.

### Blog Guidelines

#### Suitable content:
- **Original content only**
- Knative [new feature releases and project updates](#communicating-new-project-releases)
- Tutorials and demos
- Use cases
- Content that is specific to a vendor or platform about Knative installation and use

#### Unsuitable Content:
- Blogs that do not address Knative in any way
- Content that doesn't interact with Knative APIs or interfaces
- Vendor pitches

## Communicating new project releases
**Scheduled releases:** The Knative project has a release every 6 weeks, and we need your help communicating new changes to our community! If you would like to contribute a blog post to the Knative blog, please consider writing about the latest changes to the project. Ideally, there should be a single blog post for every release version, for example, 0.17; 0.18; 0.19. The title convention should be: *Version [version number] release - [date]*. Release blog contributors should write a summary of the changes and select up to 3 highlights of the current release to write about.
**Big changes to the project.** Big changes to the project require a deep dive blog that describes the new feature in detail and give examples of the new functionality.

## Review Process

After a blog post is submitted as a PR, it is automatically assigned to a reviewer.

Each blog post requires a `lgtm` label from at least one person in the editorial team. Once the necessary labels are in place, one of the reviewers will add an `approved` label, and schedule publication of the blog post.

### Service level agreement (SLA)

Blog posts can take up to **1 week** to review. If you'd like to request an expedited review, please say so on your message when you ping the editorial team on Slack.
