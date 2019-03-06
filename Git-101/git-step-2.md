Step 2: Basic Git workflows
---------------------------

When you set out to accomplish something *that you have done before*;
whether you are aware of it or not, you have workflows that you follow
to get that thing done. Developers (which now includes you) are the
same. When they need to get something done, they have workflows that
they follow. While these workflows may be new to you, they will quickly
become your own.

### Cloning a repository

When you want to work with someone else's code, you first have to get it
on your machine. We do this with the `git clone` command. For example,
when you were preparing your machine for this *Python Fundamentals*
module, we instructed you to clone (download) our `dnav3-code` sample
code repository to your machine. See the "How To Setup Your Own
Computer" link if you have not completed the setup.

> **Note:** You should have already cloned the sample code to your
> computer. Please don't do it more than once. Having multiple copies of
> the code samples on your computer can cause confusion as to which one
> you are working with.

When you clone a repository, files are copied to a folder in the
location where you run the command.

    $ git clone https://github.com/CiscoDevNet/dnav3-code

This example shows the resulting output in your terminal window:

    Cloning into 'dnav3-code'...
    remote: Counting objects: 274, done.
    remote: Compressing objects: 100% (115/115), done.
    remote: Total 274 (delta 145), reused 266 (delta 139), pack-reused 0
    Receiving objects: 100% (274/274), 1.12 MiB | 3.41 MiB/s, done.
    Resolving deltas: 100% (145/145), done.

When you ran this command, the git client on your laptop connected to
the URL provided and cloned a full copy of the `dnav3-code` repository
to your machine. By the way, when we say "clone,"