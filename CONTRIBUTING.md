# Contribution Guidelines

## 1. Team Branches

Each member must work on their assigned branch.

| Member | Branch |
|---|---|
| Member 1 – Frontend | frontend |
| Member 2 – Backend | backend |
| Member 3 – Authentication | authentication |
| Member 4 – Database | database |
| Member 5 – Integration | integration |

## 2. Before Starting Work

Update your branch:

```bash
git switch your-branch
git pull origin your-branch
```

## 3. Saving Changes

After completing your work:

```bash
git add .
git commit -m "Describe your changes"
git push origin your-branch
```

## 4. Pull Requests

1. Open the GitHub repository.
2. Select Pull requests.
3. Click New pull request.
4. Select `integration` as the base branch.
5. Select your assigned branch as the compare branch.
6. Create the pull request.
7. Wait for review and approval.

## 5. Important Rules

- Do not push directly to `main`.
- Do not push directly to `integration`.
- Work only on your assigned branch.
- Pull the latest changes before starting work.
- Communicate with teammates before changing shared files.
- Test your work before submitting a pull request.

## 6. Final Integration

Member 5 coordinates code reviews, merges approved pull requests into `integration`, and helps test the combined application.

After final testing and team approval, the completed project is merged into `main`.