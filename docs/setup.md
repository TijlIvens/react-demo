# Setup

## start

- Run:   
`npm create vite@latest <project-name>` 

- Select React
- Select TypeScript + SWC
- `cd` to the project folder
- Run: `npm install`
- Run: `npm run dev` to start the project

## MUI

- Run: `npm install @mui/material @emotion/react @emotion/styled`
- Run: `npm install @fontsource/roboto`

- [Docs](https://mui.com/material-ui/getting-started/installation/)

## Routing

- Run: `npm install react-router-dom`

- [Docs](https://reactrouter.com/en/main/start/tutorial)

- In the app file add `<RouterProvider router={router} />`

- Create a router in the [router file](/src/Router/router.tsx)

- Add all pages to this file
