Google Dorking is a technique of using advanced search operators and parameters to find specific information on the web. It can be used for security research, ethical hacking, or simply to speed up your online searching. In this cheatsheet, I will show you some basic and advanced Google Dorking commands and examples.

## Basic Google Dorking Syntax
The basic syntax for Google Dorking is:
```
operator:parameter
```
The operator specifies the type of search you want to perform, such as finding a specific site, file type, or keyword. The parameter is the value that you want to search for. For example:
```
site:github.com
```
This will search for all pages on github.com.

You can also combine multiple operators and parameters with a space to refine your search. For example:
```
site:github.com filetype:md
```
This will search for all Markdown files on github.com.

## Common Google Dorking Operators
Here are some of the most common Google Dorking operators and their usage:

| operator | Description | Example |
| ------------- | ------------- | ------------- |
| site | Searches for a specific site or domain. | site:github.com
| filetype| Searches for a specific file type or extension | filtype:pdf |
| inurl | Searches for a specific keyword or phrase in the URL. | inurl:login |
| intitle | Searches for a specific keyword or phrase in teh title. | intitle:"Google Dorking" |
| intext | Searches for a specific keyword in the text. | intext:"password" |
| link | Seaches for pages that link to a specific URL. | link:github.com |
| cache | Shows the cached version of a web page. | cache:github.com |
| related | Shows pages that are similar to a specific URL. | related:github.com |
| numrange | Searches for a range of numbers. | numrange:1-100 |
| before/after | Searches for pages that were created or updated before or after a specific date. | filetype:pdf after:2020-01-01 |

## Advanced Google Dorking Syntax
You can also use some advanced syntax to modify or combine your Google Dorking Queries. Here are some exapmles:
| Syntax | Description | Example |
| ------------- | ------------- | ------------- |
| " | Encloses a phrase or an exact match. | "Google Dorking" |
| - | Excludes a keyword or a site | -site:github.com |
| OR | Searches for either of the keywords. | filetype:pdf OR filetype:docx |
| * | Replaces one or more characters or words/ | intitle:"Google *"
| .. | Searches for a range of values. | numrange:1..100 |
| AROUND(n) | Searches for two keywords that are within n words of each other | "Google" AROUND(5) "Dorking" |
## Google Dorking Examples
Here are some Google Dorking examples that you can try for yourself. Note that some of these queries may return no results or outdated results, depending on the availability and freshness of the data.

## Security Related Dorks
These dorks can help you find sensitive information or vulnerabilities on the web.
| Query | Explanation |
| ------------- | ------------- |
| filetype:pdf password | Searches for PDF files containing the word "password". |
| intitle:index.of password.txt | Searches for websties with "index.of" in the title and the word "password.txt" |
| intext:"username" filtype:xlsx | Searches for excel files containing the word "username". |
| inurl:admin login |  Searches for webpages with "admin" and "login" in the URL. |
| intitle:"login page" "Username" "Password" | Searches for pages with "login" in the URL and the word "password" in the text. |
| inurl:.php?id= | Searches for pages containing ".php?id=" in the URL. |
| intitle:"SQL query failed" intext:"mysql" | Searches for pages with the title "SQL query failed" and the word "mysql" in the text. |
| site:.edu filetype:pdf | Searches for PDF files on ".edu" |
| intext:"Private Key" filetype:pem | Searches for files with "Private Key" in the text and the file type "pem". |
| intitle:"Index of /" +passwd | Searches for websites with "Index of /" in the title and the word "passwd" |
| intitle:"Index of /" +secret | Searches for websites with "Index of /" in the title and the word "secret" |
| intext:"Confidential" filetype:ppt | Searches for PowerPoint files with the word "Confidential" in the text. |
| intext:"Database Error" intitle:"Warning" | Searches for pages with the "Database Error" and the title "Warning".
| intext:"PHP Script" "Debug" | Searches for pages with the text "PHP Script" and the word "Debug" |

## Entertainment Related Dorks
these dorks can help you find interesting or amusing conten on the web
| Query | Explanation |
------------- | ------------- |
| intext:"index of /" Nina Simone | Searches for pages with the text "index of /" and the name "Nina Simone". |
| intitle:"index.of" "parent directory" "size" last" modified" "description" I Put A Spell On You (mp4|mp3|avi|flac|aac|ape|ogg) -inurl: (jsp|php|html|aspx|htm|csf|shtml|lyrics-realm|mp3-collection) -site:.info | Searches for a file with the name "I Put A Spell On You" in various formats, exlcuding some common false positives. |
| Bill Gates intitle:"index.of" "parent directory" "size" "last modified" "description" Microsoft (pdf|txt|epub|doc|docx) -inurl: (jsp|php|html|aspx|htm|cf|shtml|ebooks|ebook) -site:.info | Searches for files related to Bill Gates and Microsoft in various formats, excluding some common positives. |
| parent directory DVDRip -xxx -html -htm -php -shtml -opendivx -md5 -md5sums | Searches for DVDRip files in aprent directories, excluding some common false positives. |
| parent directory MP3 -xxx -html -htm -php -shtml -opendivx -md5 -md5sums | Searches for MP3 files in parent directories, excluding some common false positives. |
| parent directory Name of Singer or album -xxx -html -htm -php -shtml -opendivx -md5 -md5sums | Searches for music files of a specific singer or album in parent directories, excluding some common false positives.


## Conclusion
Google Dorking is a powerful and versatile technique that can help you find information and content on the web. However, it can also be used for malicious purposes, such as hacking or stealing data. Therefore, you should always be careful and ethical when using Google Dorking, and protect your own online resources from being exposed by Google Dorking. For more information and resources on Google Dorking, you can check out the following links:

[The Ultimate Google Dorking Cheat Sheet - 2023](https://usersearch.org/updates/2023/02/05/the-ultimate-google-dorking-cheatsheet-2023/)

[Google dork cheatsheet · GitHub](https://gist.github.com/sundowndev/283efaddbcf896ab405488330d1bbc06)

[Google Dorks Cheat Sheet 2023: How to Hack Using Google - StationX](https://www.stationx.net/google-dorks-cheat-sheet/)

[Google Dorking Hacking and Defense Cheat Sheet - SANS Institute](https://www.sans.org/posters/google-hacking-and-defense-cheat-sheet/)

[Basic writing and formatting syntax - GitHub Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

[Quickstart for writing on GitHub - GitHub Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)
