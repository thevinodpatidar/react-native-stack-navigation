# React-Native Stack Navigation Boilerplate

# Getting Started with React-Native

## Installation:

[Setting up the development environment · React Native](https://reactnative.dev/docs/environment-setup)

## Setup:

```bash
npm install react-native-cli -g
```

### Clone the project:

```bash
git clone https://github.com/vinodpatidar123/react-native-stack-navigation.git APP_NAME
```

Change the directory:

```bash
cd APP_NAME
```

Install dependencies using yarn or npm:

```bash
yarn
```

Rename the entire boilerplate to your project name:
```bash
yarn run rename -- PROJECT_NAME
```

Remove current git instance and re-initailse:
```bash
rm -rf .git/ && git init
```

Install the app to your AVD or mobile (connected thru USB):

```bash
yarn android
```

Start Metro server and make these server running while development. (metro is a bundler for react-native):

```bash
yarn start
```

## Choose to setup type of navigation

- Stack Navigation
- Bottom Tab Navigation
- Drawer Navigation
- Authentication

## Stack Navigation:

### Get Stack Navigation branch from github in master.

```bash
git pull origin stack-navigation
```

## Bottom Tab Navigation:

### Get Bottom Tab Navigation branch from github in master.

```bash
git pull origin bottom-tab-navigation
```

## Drawer Navigation:

### Get Drawer Navigation branch from github in master.

```bash
git pull origin drawer-navigation
```

## Authentication:

### Get Authentication branch from github in master.

```bash
git pull origin authentication
```