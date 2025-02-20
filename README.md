# React Router Dom v6 Catch All Route Not Working

This repository demonstrates a common issue in React Router v6 where the catch-all route (`path="*"`) within the `Routes` component fails to function correctly.  The problem arises when other routes might seem to conflict, making the catch all route ineffective. The solution involves carefully placing the catch-all route at the end of the `Routes` definition to ensure it only matches if no other route does. 

## Setup

1. Clone the repo
2. Run `npm install`
3. Run `npm start`