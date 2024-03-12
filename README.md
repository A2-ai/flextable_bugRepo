Rendering the flextable.qmd within this repository results in the following, intended outcome:

![Screenshot 2024-03-12 at 9 47 50 AM](https://github.com/A2-ai/flextable_bugRepo/assets/135846021/5ce81de1-7e32-4d36-883a-68c50eb96a9e)

However, when working in the rendered .docx file going forward, the user is unable to cross-reference the table using the appropriate insert cross-reference option within Microsoft Word:

![Screenshot 2024-03-12 at 9 50 58 AM](https://github.com/A2-ai/flextable_bugRepo/assets/135846021/408ac3f9-7cdb-430a-ab64-6ec48acb14f3)

Instead, a user is able to insert a cross-reference using the bookmark tab within Microsoft Word's cross-reference option, but the outcome is a duplication of the table environment, not the caption:

![Screenshot 2024-03-12 at 9 58 29 AM](https://github.com/A2-ai/flextable_bugRepo/assets/135846021/d7c26ff0-a8f9-401d-a61d-2dfa8e3e5d7e)

![Screenshot 2024-03-12 at 10 05 43 AM](https://github.com/A2-ai/flextable_bugRepo/assets/135846021/260eeec3-86eb-4f1d-b3c4-1f8cb9502e08)

This outcome is not intended. 

The desired outcome is the following:

![Screenshot 2024-03-12 at 10 17 52 AM](https://github.com/A2-ai/flextable_bugRepo/assets/135846021/de18cbc5-d1ae-49c7-8396-b417427fc467)

Checklist:

Software Details:

OS:

macOS Sonoma 14.4

flextable:

flextable_0.9.3

Rstudio:

RStudio 2023.09.0+463.pro11 "Desert Sunflower" Release (6cc4ae5fce128156206f7e29378b7b165770ff63, 2023-09-24) for Ubuntu Focal
Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.0.0 Safari/537.36

sessionInfo:

R version 4.3.1 (2023-06-16)
Platform: x86_64-pc-linux-gnu (64-bit)
Running under: Ubuntu 20.04.6 LTS

Quarto:

Quarto 1.4.551
[✓] Checking versions of quarto binary dependencies...
      Pandoc version 3.1.11: OK
      Dart Sass version 1.69.5: OK
      Deno version 1.37.2: OK

[✓] Checking Quarto installation......OK
      Version: 1.4.551

[✓] Checking R installation...........OK
      Version: 4.3.1
      knitr: 1.45
      rmarkdown: 2.25
