### Full stack React CRUD app - Golfers

#Resources 

##Golfers 

##Routes table

| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| GET    | `/golfers`                | `golfers#index`    |
| GET    | `/golfers/:id`            | `golfers#show`    |
| POST   | `/golfers`                | `golfers#create`    |
| PATCH  | `/golfers/:id`            | `golfers#update`  |
| DELETE | `/golfers/:id`            | `golfers#delete`   |


##Users 
##Routes

| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| POST   | `/sign-up`             | `users#signup`    |
| POST   | `/sign-in`             | `users#signin`    |
| PATCH  | `/change-password/`    | `users#changepw`  |
| DELETE | `/sign-out`            | `users#signout`   |


##Stats

#Routes
 
The routes for all the golfers STATS

| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| POST   | `/stats/:golferId`         | `stats#create`    |
| PATCH  | `/stats/:golferId/:statId`  | `stats#update`  |
| DELETE | `/stats/:golferId/:statId`   | `stats#delete`   |# 
