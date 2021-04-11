# MyResumeBuilder
A repo to auto generate Resume .pdf files from my Resume.md on commit using pandoc alpine docker container in Github Actions. <br/>
(*this action could would for diffrent files and formats but not tested*)

<br/>

# To do
---
- [x] Horizontal rules to spand the whole document 
- [ ] get page ends working to make making new pages easier 
- [ ] Find best google font and refine action code 
- [ ] custom sizing of diffrent headers to make it more visually appealing (not much visuall size diffrence between h1 and h3)
- [ ] change character for sub sub dotpoints
- [x] clone file from a private repo to keep security
  - [ ]  ~~push file from container when finished to keep security~~ - replaced with redaction 
  - [ ]  Implement Latex *`censor`* package to redact automatically redact text
