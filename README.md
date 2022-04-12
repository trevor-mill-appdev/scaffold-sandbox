# Scaffold Sandbox

## Scaffold

Try the `scaffold` generator:

```
rails generate scaffold movie title:string description:text
```

[Compare the output with the `draft:resource` generator's output.](https://github.com/raghubetina/movie-resource/pull/1/files)

Do you understand every line of `scaffold`? Ask lots of questions.

## Devise

[Add Devise](https://chapters.firstdraft.com/chapters/880) and try generating a Devise model.

```
rails g devise user username:string avatar_url:string
```

This does something similar to `rails g draft:account`, but a _lot_ better. Try out the `current_user` helper method that Devise provides.
