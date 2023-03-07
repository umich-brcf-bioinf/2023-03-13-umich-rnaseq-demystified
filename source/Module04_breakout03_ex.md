---
title: "Breakout 03"
author: "UM Bioinformatics Core"
output:
        html_document:
            includes:
                in_header: header.html
            theme: paper
            fig_caption: true
            markdown: GFM
            code_download: true
---
<style type="text/css">
body{ /* Normal  */
      font-size: 14pt;
  }
pre {
  font-size: 12pt
}
</style>

<br>

## Transfer MultiQC Report With `scp` Exercise (Breakout)

<br>

**15 Minutes**

<br>

We just tried two new variations of our MultiQC command, one pointed at the directory of our trimmed FastQC results, and another at the whole project directory. For convenience, we've included these reports in the zipped folder you downloaded at the beginning of the class. However, it's also useful to know how to transfer data to/from a remote instance. We'll explore how to use `scp` in this exercise.

<br>

### Instructions:

<br>

- Make sure that you are viewing your local terminal. The `scp` command should be run from your own machine.
- Use `scp` to transfer the comprehensive multiQC report from the AWS machine to your personal computer.
- Confirm that you've received the report

<br>

> Hint: The command format is:
>
> ~~~
> scp source destination
> ~~~
>
> You will need to provide your ssh login information to complete the transfer

<br>
