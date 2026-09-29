# React Contact List — Architecture & State Evolution

A modular Contact List (CRUD) application showcasing how state management, asynchronous data fetching, and component paradigms evolve in modern React development.

Each branch represents a standalone iteration demonstrating a specific pattern or library integration.

---

## Branches Overview

| Branch | Focus / Architecture | Key Technologies |
| :--- | :--- | :--- |
| [`classComponent`](https://github.com/AppRangejn/react-contact-list-evolution/tree/classComponent) | Legacy lifecycle methods & local state | React Class Components, Lifecycle hooks |
| [`functionComponent`](https://github.com/AppRangejn/react-contact-list-evolution/tree/functionComponent) | Functional approach with hooks | React Hooks (`useState`, `useEffect`) |
| [`axios`](https://github.com/AppRangejn/react-contact-list-evolution/tree/axios) | REST API integration | Axios, REST endpoints |
| [`mui-formik-yup`](https://github.com/AppRangejn/react-contact-list-evolution/tree/mui-formik-yup) | Accessible UI & declarative form validation | Material UI (MUI), Formik, Yup |
| [`redux`](https://github.com/AppRangejn/react-contact-list-evolution/tree/redux) | Classical Redux flux flow | Redux, `connect` / `useDispatch`, action creators |
| [`redux-toolkit`](https://github.com/AppRangejn/react-contact-list-evolution/tree/redux-toolkit) | Modern standardized Redux | Redux Toolkit (`createSlice`, `createAsyncThunk`) |
| [`saga`](https://github.com/AppRangejn/react-contact-list-evolution/tree/saga) | Generator-based side effect orchestration | Redux-Saga (`takeEvery`, `call`, `put`) |

---

## Getting Started

Clone the repository and switch to the branch you want to inspect:

```bash
# Clone repository
git clone https://github.com/AppRangejn/react-contact-list-evolution.git

# Enter project directory
cd react-contact-list-evolution

# Checkout target branch
git checkout redux-toolkit

# Install dependencies and run
npm install
npm start
```
