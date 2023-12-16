# download-page-in-pdf

#### Required Modules :
  - pyppdf
    ```bash
      pip3 install pyppdf
    ```
  - pyppyteer 
    ```bash
      pip3 install pyppeteer
    ```

 #### Examples of use :
 - Download a page:
 ```bash
    python download-page-as-pdf.py -l 'www.github.com'
 ```

 - Download a page and give a pdf name:
 ```bash
    python download-page-as-pdf.py -l 'github.com/cmdkernel' -n 'github_user.pdf'
 ```
