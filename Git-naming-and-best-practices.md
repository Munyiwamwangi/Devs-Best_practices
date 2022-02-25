## Branch Naming

Branches created should be named using the following format:

``` {story type}-{2-3 word summary}-{pivotal tracker id} ```

story-type - Indicates the context of the branch and should be one of:

* ft == Feature
* bg == Bug
* ch == Chore
* rf == Refactor

story-summary - Short 2-3 words summary about what the branch contains

### Example

``` ft-resources-rest-endpoints-111504508 ```

## Commits

Atomic commits should be made with the format:

``` <type>(<scope>): <subject>``<BLANK LINE> <body> <BLANK LINE> <footer> ```


## Example
```
chore(coveralls):add coveralls yml
[Finishes #153742460]

```

## PR Naming

The PR title should be named using the following format:

#[STORY_ID] Story description

## Example

``` #111504508 Buildout REST Endpoints for Resources (CRUD) ```

PR Description Template (Markdown)

The description of the PR should contain the following headings and corresponding content in Markdown format.

#### What does this PR do?
#### Description of Task to be completed?
#### How should this be manually tested?
#### Any background context you want to provide?
#### What are the relevant pivotal tracker stories?
#### Screenshots (if appropriate)
#### Questions:

## Example
![PR](https://res.cloudinary.com/dakhp08gq/image/upload/v1607605614/Screenshot_2020-12-10_at_16.04.22.png)