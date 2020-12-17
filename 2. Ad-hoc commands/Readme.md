# Ad Hoc Commands

Ad Hoc commands are simple commands to run ansible tasks quickly.

```text
$ ansible host-pattern -m module [-a 'module arguments'] [-i inventory]
```

We have already used a command, while checking the connection. Lets analyse it,

```text
$ ansible all -m ping
```

In this 