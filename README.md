# everand-downloader
Download your books from Everand in PDF format for personal and offline use, and because fuck Everand.

### Please note:
1) this is a very first version, so expect bugs to happen. Please ~~report them opening a new issue~~ learn some Python and deal with it. :P
2) only Everand **eBooks** are supported for now (no PDF Documents/Audiobooks etc.)

## Installation

Install the required Python libraries:

  >$ pip install PyPDF2

Install Playwright for Python:
  
  >$ pip install playwright
  
  >$ playwright install

## Running

1) Run the script:

>$ py fuck_everand.py

2) A browser instance will open. Proceed with the login on Everand and make sure to solve the captcha (if any). This step is required only for the first run. If you later want to login with another account, delete the session.json file and re-run the script. You may also have to do 2FA for each run.

3) The script will grab the list of books in your saved list on Everand. Why not go ahead and save a load more stuff you always fancied reading before running this, because fuck Everand.

3) The script will start downloading each Everand ebook type book - scribd stuff and PDFs are not supported, but all Everand ebooks including sheet music should work fine.

## TODO:
- [X] Scale/reduce pdf page size
- [ ] Fuck Everand

# DISCLAIMER:
The code is not intended for piracy or unlawful re-sharing purposes. You can only download the books you have purchased for the sole purpose of personal use. I do not take responsibility for illegal use of the software. But fuck Everand.
