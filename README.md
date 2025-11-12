# good-news-aggregator1
Aggregator of positive news with admin panel and user preferences



## Database Diagram

![Database Diagram](BD_GoodNews.jpg)

This database diagram represents the structure of the **Good News Aggregator** project.

- **Users** – Stores user accounts and roles.
- **Subscriptions** – Each user can have one subscription (1:1).
- **News** – Aggregated news articles with positivity score.
- **Sources** – News sources from which data is collected.
- **Categories** – Tags for classifying news.
- **Comments** – Users can comment on news (1:M relationship).
- **Reactions** – Users can react to news or comments.
- **ReactionsType** – Defines the types of reactions available in the system (e.g., Like, Dislike, Heart).
