# Reading Notes 07
Notes from:
https://gist.github.com/brookr/5977550

## Who is Roy Fielding?
Roy Fielding is a guy who helped write the first web servers, that sent documents across the internet. He did a ton of research explaining why the web works the way it does. His name is on the specification for the protocol that is used to get pages from servers to browsers.

## Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?
Machines don’t have a universal noun. Every programming language, database, or other kind of system has a different way of talking about nouns. That's why the URL is so important. It lets all of these systems tell each other about each other's nouns.

## What is the HTTP protocol that Fielding and his friends created?
It is a general purpose protocol for applying verbs to pronouns. It tells the machine what verbs to apply to nouns like GET, PATCH, PUT, etc.

## What does a GET do?
Systems use HTTP GET to retrieve information from each other.

## What does a POST do?
If one system needs to add something to another system it would use HTTP POST.

## What does PUT do?
If a system needs to replace something in another system it would use HTTP PUT.

## What does PATCH do?
If a system needs to do a partial update on another system it will use HTTP PATCH.
