# Blog Posts

{% api-method method="get" host="https://api.titan.tf/v1/blogs/" path="page/limit" %}
{% api-method-summary %}
Get Blog Posts
{% endapi-method-summary %}

{% api-method-description %}
Retrieve a list of blog posts.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="page" type="integer" required=true %}
Page number to retrieve
{% endapi-method-parameter %}

{% api-method-parameter name="limit" type="integer" required=true %}
Number of blog posts on each page
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
  "result": [
    {
      "id": "10",
      "title": "Introducing Job Market",
      "content": "We love the new missions feature we introduced to you last week. We now bring you the Job Market, a.k.a solo missions!   Choose Your Own Adventure What job you decide to take is completely up to you! Nobody is forcing you to take up a job you don't like...",
      "date": "1589732519"
    },
    {
      "id": "53",
      "title": "Introducing Missions",
      "content": "Work together as a team to complete the team mission before the other team does within the time limit!   When there are 6 or more players, missions may start to appear. They have a 40% chance of appearing. The objectives of both teams will be the same. ...",
      "date": "1589123854"
    },
    {
      "id": "65",
      "title": "Server Updates — May 2020 (Complete)",
      "content": "This blog post will update as things changes.  Last Update: 1 May 10:19 AM SGT (+0800)   Legend Server is pending migration, addition or removal on Apr 30 Server is pending update Server has been migrated successfully Server has been removed   New (Sing...",
      "date": "1588044246"
    },
    {
      "id": "64",
      "title": "Server Migration for Performance — May 2020",
      "content": "In order to build a more maintainable network of servers, we have decided to make some changes to our existing infrastructure.  Our OG servers are hosted on not so ideal machine specs but they are definitely playable. OG servers refer to all of our orig...",
      "date": "1587695614"
    },
    {
      "id": "60",
      "title": "Free Titan Plus Month StayHome",
      "content": "In light of the Covid-19 situation, we would like to give everyone a month of free access to Titan Plus. By supplying this gift to everyone out of our generosity, we hope that everyone will continue to stay safe, stay home and have fun on our servers.  ...",
      "date": "1586604854"
    }
  ],
  "success": "true",
  "errors": [
    
  ]
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://api.titan.tf/v1/blog/" path="id" %}
{% api-method-summary %}
Get Blog Post
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="id" type="integer" required=true %}
Id of blog post to retrieve
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```
{
  "result": {
    "id": "1",
    "title": "Tour of Destruction",
    "content": "There isn't enough destruction. The thirst for destruction must be _quenched_.   Play on this 2 month long event based in Mann vs Machine, from December 25th to March 1st, and earn limited time rewards!    !(https://media.discordapp.net/attachments/4655...",
    "date": "1545728067"
  },
  "success": "true",
  "errors": [
    
  ]
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

