This is a currency converter project using api,In this project i make a custom hook which includes the logic about fatching api data. seperating the logic in small projects may not differenciate much on aspect of reusebility , cleaner codeing or abstarcting . although doing this project, here are the points i have learned so far about custom hooks.

# custom hooks in react

-A custom Hooks is a javascript function ,which is used to remove the dulpicated logic in components and we can extract that logic from custom hook.It allows us to extract and share functionality like state management, side effects ,fetching data from api or event handling .

# Reuse logic

promotes code reusability and makes it easier to maintain and update shared functionlity

# abstraction

abstract away implementation details.

# Shareable across components

# Better organization

-As ours component logic grows ,it's benificial to organize it into smaller and manageable pieces .

# Avoide prop driling

-In some cases ,custom hooks can help avoid prop drilling -passing data through multiple layeers of components just to react a deeply nested child
