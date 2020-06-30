# actions-contexts

This is an observation to try and list the context provided by GitHub Actions

## Runner

Common to all event types

<details>
<summary>View</summary>

```json
{
  "os": "Linux",
  "tool_cache": "/opt/hostedtoolcache",
  "temp": "/home/runner/work/_temp",
  "workspace": "/home/runner/work/actions-contexts"
}
```
</details>

## Push

Pushed a commit named "First commit"

<details>
<summary>View</summary>

```json
{
  "token": "***",
  "job": "echo-context",
  "ref": "refs/heads/master",
  "sha": "db53e06f73c0d62e7df04f352f620ffaddf787f0",
  "repository": "mtsgi/actions-contexts",
  "repository_owner": "mtsgi",
  "repositoryUrl": "git://github.com/mtsgi/actions-contexts.git",
  "run_id": "151781003",
  "run_number": "1",
  "actor": "mtsgi",
  "workflow": "Push Event",
  "head_ref": "",
  "base_ref": "",
  "event_name": "push",
  "event": {
    "after": "db53e06f73c0d62e7df04f352f620ffaddf787f0",
    "base_ref": null,
    "before": "0000000000000000000000000000000000000000",
    "commits": [
      {
        "author": {
          "email": "example@example.com",
          "name": "mtsgi",
          "username": "mtsgi"
        },
        "committer": {
          "email": "example@example.com",
          "name": "mtsgi",
          "username": "mtsgi"
        },
        "distinct": true,
        "id": "db53e06f73c0d62e7df04f352f620ffaddf787f0",
        "message": "First commit",
        "timestamp": "2020-06-30T03:01:45+09:00",
        "tree_id": "0a725a7c177056daec59c732bd737d2016681282",
        "url": "https://github.com/mtsgi/actions-contexts/commit/db53e06f73c0d62e7df04f352f620ffaddf787f0"
      }
    ],
    "compare": "https://github.com/mtsgi/actions-contexts/commit/db53e06f73c0",
    "created": true,
    "deleted": false,
    "forced": false,
    "head_commit": {
      "author": {
        "email": "example@example.com",
        "name": "mtsgi",
        "username": "mtsgi"
      },
      "committer": {
        "email": "example@example.com",
        "name": "mtsgi",
        "username": "mtsgi"
      },
      "distinct": true,
      "id": "db53e06f73c0d62e7df04f352f620ffaddf787f0",
      "message": "First commit",
      "timestamp": "2020-06-30T03:01:45+09:00",
      "tree_id": "0a725a7c177056daec59c732bd737d2016681282",
      "url": "https://github.com/mtsgi/actions-contexts/commit/db53e06f73c0d62e7df04f352f620ffaddf787f0"
    },
    "pusher": {
      "email": "example@example.com",
      "name": "mtsgi"
    },
    "ref": "refs/heads/master",
    "repository": {
      "archive_url": "https://api.github.com/repos/mtsgi/actions-contexts/{archive_format}{/ref}",
      "archived": false,
      "assignees_url": "https://api.github.com/repos/mtsgi/actions-contexts/assignees{/user}",
      "blobs_url": "https://api.github.com/repos/mtsgi/actions-contexts/git/blobs{/sha}",
      "branches_url": "https://api.github.com/repos/mtsgi/actions-contexts/branches{/branch}",
      "clone_url": "https://github.com/mtsgi/actions-contexts.git",
      "collaborators_url": "https://api.github.com/repos/mtsgi/actions-contexts/collaborators{/collaborator}",
      "comments_url": "https://api.github.com/repos/mtsgi/actions-contexts/comments{/number}",
      "commits_url": "https://api.github.com/repos/mtsgi/actions-contexts/commits{/sha}",
      "compare_url": "https://api.github.com/repos/mtsgi/actions-contexts/compare/{base}...{head}",
      "contents_url": "https://api.github.com/repos/mtsgi/actions-contexts/contents/{+path}",
      "contributors_url": "https://api.github.com/repos/mtsgi/actions-contexts/contributors",
      "created_at": 1593453672,
      "default_branch": "master",
      "deployments_url": "https://api.github.com/repos/mtsgi/actions-contexts/deployments",
      "description": "Contexts of GitHub Actions",
      "disabled": false,
      "downloads_url": "https://api.github.com/repos/mtsgi/actions-contexts/downloads",
      "events_url": "https://api.github.com/repos/mtsgi/actions-contexts/events",
      "fork": false,
      "forks": 0,
      "forks_count": 0,
      "forks_url": "https://api.github.com/repos/mtsgi/actions-contexts/forks",
      "full_name": "mtsgi/actions-contexts",
      "git_commits_url": "https://api.github.com/repos/mtsgi/actions-contexts/git/commits{/sha}",
      "git_refs_url": "https://api.github.com/repos/mtsgi/actions-contexts/git/refs{/sha}",
      "git_tags_url": "https://api.github.com/repos/mtsgi/actions-contexts/git/tags{/sha}",
      "git_url": "git://github.com/mtsgi/actions-contexts.git",
      "has_downloads": true,
      "has_issues": true,
      "has_pages": false,
      "has_projects": true,
      "has_wiki": true,
      "homepage": null,
      "hooks_url": "https://api.github.com/repos/mtsgi/actions-contexts/hooks",
      "html_url": "https://github.com/mtsgi/actions-contexts",
      "id": 275889731,
      "issue_comment_url": "https://api.github.com/repos/mtsgi/actions-contexts/issues/comments{/number}",
      "issue_events_url": "https://api.github.com/repos/mtsgi/actions-contexts/issues/events{/number}",
      "issues_url": "https://api.github.com/repos/mtsgi/actions-contexts/issues{/number}",
      "keys_url": "https://api.github.com/repos/mtsgi/actions-contexts/keys{/key_id}",
      "labels_url": "https://api.github.com/repos/mtsgi/actions-contexts/labels{/name}",
      "language": null,
      "languages_url": "https://api.github.com/repos/mtsgi/actions-contexts/languages",
      "license": null,
      "master_branch": "master",
      "merges_url": "https://api.github.com/repos/mtsgi/actions-contexts/merges",
      "milestones_url": "https://api.github.com/repos/mtsgi/actions-contexts/milestones{/number}",
      "mirror_url": null,
      "name": "actions-contexts",
      "node_id": "MDEwOlJlcG9zaXRvcnkyNzU4ODk3MzE=",
      "notifications_url": "https://api.github.com/repos/mtsgi/actions-contexts/notifications{?since,all,participating}",
      "open_issues": 0,
      "open_issues_count": 0,
      "owner": {
        "avatar_url": "https://avatars3.githubusercontent.com/u/29329023?v=4",
        "email": "example@example.com",
        "events_url": "https://api.github.com/users/mtsgi/events{/privacy}",
        "followers_url": "https://api.github.com/users/mtsgi/followers",
        "following_url": "https://api.github.com/users/mtsgi/following{/other_user}",
        "gists_url": "https://api.github.com/users/mtsgi/gists{/gist_id}",
        "gravatar_id": "",
        "html_url": "https://github.com/mtsgi",
        "id": 29329023,
        "login": "mtsgi",
        "name": "mtsgi",
        "node_id": "MDQ6VXNlcjI5MzI5MDIz",
        "organizations_url": "https://api.github.com/users/mtsgi/orgs",
        "received_events_url": "https://api.github.com/users/mtsgi/received_events",
        "repos_url": "https://api.github.com/users/mtsgi/repos",
        "site_admin": false,
        "starred_url": "https://api.github.com/users/mtsgi/starred{/owner}{/repo}",
        "subscriptions_url": "https://api.github.com/users/mtsgi/subscriptions",
        "type": "User",
        "url": "https://api.github.com/users/mtsgi"
      },
      "private": false,
      "pulls_url": "https://api.github.com/repos/mtsgi/actions-contexts/pulls{/number}",
      "pushed_at": 1593453713,
      "releases_url": "https://api.github.com/repos/mtsgi/actions-contexts/releases{/id}",
      "size": 0,
      "ssh_url": "git@github.com:mtsgi/actions-contexts.git",
      "stargazers": 0,
      "stargazers_count": 0,
      "stargazers_url": "https://api.github.com/repos/mtsgi/actions-contexts/stargazers",
      "statuses_url": "https://api.github.com/repos/mtsgi/actions-contexts/statuses/{sha}",
      "subscribers_url": "https://api.github.com/repos/mtsgi/actions-contexts/subscribers",
      "subscription_url": "https://api.github.com/repos/mtsgi/actions-contexts/subscription",
      "svn_url": "https://github.com/mtsgi/actions-contexts",
      "tags_url": "https://api.github.com/repos/mtsgi/actions-contexts/tags",
      "teams_url": "https://api.github.com/repos/mtsgi/actions-contexts/teams",
      "trees_url": "https://api.github.com/repos/mtsgi/actions-contexts/git/trees{/sha}",
      "updated_at": "2020-06-29T18:01:12Z",
      "url": "https://github.com/mtsgi/actions-contexts",
      "watchers": 0,
      "watchers_count": 0
    },
    "sender": {
      "avatar_url": "https://avatars3.githubusercontent.com/u/29329023?v=4",
      "events_url": "https://api.github.com/users/mtsgi/events{/privacy}",
      "followers_url": "https://api.github.com/users/mtsgi/followers",
      "following_url": "https://api.github.com/users/mtsgi/following{/other_user}",
      "gists_url": "https://api.github.com/users/mtsgi/gists{/gist_id}",
      "gravatar_id": "",
      "html_url": "https://github.com/mtsgi",
      "id": 29329023,
      "login": "mtsgi",
      "node_id": "MDQ6VXNlcjI5MzI5MDIz",
      "organizations_url": "https://api.github.com/users/mtsgi/orgs",
      "received_events_url": "https://api.github.com/users/mtsgi/received_events",
      "repos_url": "https://api.github.com/users/mtsgi/repos",
      "site_admin": false,
      "starred_url": "https://api.github.com/users/mtsgi/starred{/owner}{/repo}",
      "subscriptions_url": "https://api.github.com/users/mtsgi/subscriptions",
      "type": "User",
      "url": "https://api.github.com/users/mtsgi"
    }
  },
  "server_url": "https://github.com",
  "api_url": "https://api.github.com",
  "graphql_url": "https://api.github.com/graphql",
  "workspace": "/home/runner/work/actions-contexts/actions-contexts",
  "action": "run",
  "event_path": "/home/runner/work/_temp/_github_workflow/event.json"
}
```
</details>
