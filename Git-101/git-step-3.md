Step 3: The DevNet sample-code workflow
---------------------------------------

Now that you have learned some of the basic Git workflows, unbeknownst
to you, you have already learned a *macro workflow* - a workflow that
provides a consistent process to get larger portions of work done.

![Memorize Git Commands]

*[Image Source: xkcd.com]*

***Anytime you need to:***

1.  Download (clone) a local copy of a remote repository to your
    workstation.
2.  Create a "safe place" (branch) for you to make edits.
3.  Save (commit) your incremental changes.

...you now have a workflow to get that done.

![Git Sample-Code Workflow]

To accomplish this macro workflow, we did the following:

<table>
<thead>
<tr class="header">
<th style="text-align: left;">Step</th>
<th style="text-align: left;">Action</th>
<th style="text-align: left;">Git Commands</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">1</td>
<td style="text-align: left;">Clone the Remote Repository</td>
<td style="text-align: left;"><code>git clone &lt;url&gt;</code></td>
</tr>
<tr class="even">
<td style="text-align: left;">2</td>
<td style="text-align: left;">Create and Checkout a Local Branch</td>
<td style="text-align: left;"><code>git checkout -b &lt;new branch name&gt;</code></td>
</tr>
<tr class="odd">
<td style="text-align: left;">3</td>
<td style="text-align: left;">Incrementally Commit Changes</td>
<td style="text-align: left;"><code>git add &lt;new or modified file&gt;</code><br />
<code>git commit -m "Commit Message"</code></td>
</tr>
</tbody>
</table>


<a href="/lab/git-basic-workflows/step/3" class="btn btn-success btn-sm btn-next ng-scope"><em></em></a>

  [Memorize Git Commands]: https://learninglabs.cisco.com/posts/files/git-basic-workflows/assets/images/git-memorize-commands.png
  [Image Source: xkcd.com]: https://www.xkcd.com/1597/
  [Git Sample-Code Workflow]: https://learninglabs.cisco.com/posts/files/git-basic-workflows/assets/images/git-sample-code-workflow.png