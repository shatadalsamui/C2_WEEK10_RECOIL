# Recoil State Management Demo

This project demonstrates Facebook's Recoil library for state management in React applications.

## Key Features

- **Atom-based State**: Using Recoil's atomic state management
- **State Isolation**: Components only subscribe to state they need
- **Performance Optimized**: Minimizes unnecessary re-renders
- **Counter Example**:
  - Increase button (+1)
  - Decrease button (-1)
  - Current value display

## Core Concepts

1. **Atoms**: Units of state that components can subscribe to
2. **RecoilRoot**: Provider component that makes state available
3. **useRecoilValue**: Hook to read state values
4. **useSetRecoilState**: Hook to update state

## How to Run

1. Install dependencies (including Recoil):
```bash
npm install recoil
npm install
```

2. Start development server:
```bash
npm run dev
```

3. Open [http://localhost:5173](http://localhost:5173)

## Why Recoil?

- More scalable than Context API for complex state
- Finer-grained updates than Redux
- Simple API similar to React's built-in hooks


