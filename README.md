# jira-client-workflow
template doc for using jira client in linux

# rationale:

This page provide the fondamentals for a workflow with JIRA golang client https://github.com/go-jira/jira


I will not go throught the setup doc, which is provided by upstream.

In this doc, `TEAM` is a fake name for your project name or issue-names etc. Uses it as placeholder and change it accordingly

# Fondamentals:

1) List my issue open from Project

```
jira l
ist -p TEAM -u dmaiocchi  -S open
```

2) Open issue in browser:

```
jira browse TEAM-23
```

3) View Issue details:

```
 jira view TEAM-23
```

4) Use `jira help` for listing all possible thing you can do 
