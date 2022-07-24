# CheeZJokes App

## Solution Notes

    For this exercise I used starter files for a prior version of React (16.14.0) for compatability.
    mkdir react_dad_jokes && cd react_dad_jokes && mkdir dad_jokes && cd dad_jokes
    copy starter files from recommended download for prior version

```
https://www.springboard.com/archeio/download/7f23f4f374db4e66a4384b6e47201217/
```

    npm install

## Exercise instructions and requirements

    We’ve built an app that lets people view and vote on cheesy jokes. To generate jokes, it uses the ICanHazDadJoke API.

    When the page loads, the application fetches 10 jokes, making sure that no joke appears more than once on the page.

    The application lists the jokes, along with a “vote-up” button, a “vote-down” button, and the net score (up - down) for each joke. Users can vote, and the net score updates.

    Right now, the application is written using hooks and function components. Let’s refactor the app to use class components.
