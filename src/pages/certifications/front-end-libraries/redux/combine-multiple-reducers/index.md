---
title: Combine Multiple Reducers
---
## Combine Multiple Reducers

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/front-end-libraries/redux/combine-multiple-reducers/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
#  Create Redux: Combine Multiple Reducers

## Step 1: create a rootReducer() function

``` javascript 
const rootReducer = redux.combineReducers({

});
```
## Step 2: Assign authReducer() to a key called auth in  the combineReducers method.

``` javascript 
const rootReducer = redux.combineReducers({
auth: authReducer
});
```
## Step 3:  Assign  counterReducer() to a key called count  in  the combineReducers method.
``` javascript 
const rootReducer = redux.combineReducers({
auth: authReducer,
count: counterReducer
});
```
