# Offboarding

When offboarding an employee, prioritize the revocation of access to ensure data security. Follow these steps in order of severity:

1. Remove Google Workspace access by suspending the user.
https://admin.google.com/ac/users
2. Revoke AWS access.
https://us-east-1.console.aws.amazon.com/iam/home?region=us-east-1#/users
3. Revoke GCP access.
Since GCP is using Google Workspace for authentication, access will be disabled from step 1.
4. Disable Github access by removing the user.
https://github.com/orgs/OrgName/people
    1. You can then remove the seat
    https://github.com/organizations/OrgName/settings/billing/remove_seats
5. Revoke Notion access.
Unfortunately there is no direct link so save time 😥
You need to go to Settings → Members → Access Level.
6. Disable account on Slack
https://OrgName.slack.com/admin
