# Frontend Live Coding Challenge

## Repository
Clone the following repository to get started:
[GitHub - fe-interview](https://github.com/frankudoags/fe-interview)
```bash
git clone https://github.com/frankudoags/fe-interview.git
cd fe-interview
```

## API to Use
- **Base URL:** [https://randomuser.me/api/](https://randomuser.me/api/)
- **Documentation:** [Random User API Docs](https://randomuser.me/documentation#pagination)
- **Query Parameter:**
  - `results=5` → Fetches 5 users

## Task Description
You are required to build a React component that fetches and displays random users using the **Random User API**.

### Requirements
1. Fetch 5 random users **on component mount**.
2. Display a **loading state** while fetching data.
3. Handle and display errors if the request fails.
4. Render the following user details in a list:
   - **Username**
   - **Email**
   - **Profile Picture (thumbnail)**

## Bonus (Optional Enhancements)
- Implement **retry logic** if the request fails.
- Add a **"Refresh Users"** button to fetch new users.
- Improve UI with basic styling.

## Expected Output Example
If successful, the component should display:
```
Loading... (if fetching data)
```
or
```
- JohnDoe (johndoe@example.com) [Profile Image]
- JaneSmith (janesmith@example.com) [Profile Image]
...
```

