# Challenge: automate pitching/proposal and its followup 

1. check CR sheet. prioritization - fu proposals, fu pitches, news, custom priorities - column day by day - how to make this reliable??? use dates in iso format for priority column??? @amit - how do we tackle expired tasks? (possible to send daily email with expired tasks); how do we tackle empty last action to avoid marketing efforts with CRs going idle

2. follow-up with abstract and socog toolkit
    * @chiara use packages googlesheet to connect to clinical specialties and abstracts - separate script sdblending (connect to sheet, export data as csv, package git2r to automatically add/commit/push) - 1. retrieve 2. check and mark the good and bad ones ones 3. create models for decision support in terms of selection
    
    * @chiara rismed to combine key words with clinical specialty and clincal topic and generate links - commit as separate file on sdblending/R
    * meeting scheduled for Tuesday afternoon @chiara - on 2018-01-22 contact @chico to learn about how to create functions and use expandgrid - https://stackoverflow.com/questions/48159471/iteration-using-map-for-parameter-values/48159661#48159661
    * check clinical/abstract g sheet . match clinical specialties with list for infographics - include subspecialties (orthopedic::spine, vascular::aesthetic) - dplyr regex to locate files under infographics directory to locate all infographics for a given specialty or subspecialty -- coredata_methods_clinicalapplication
    * @lucas connection to package blastula - mailgun https://github.com/rich-iannone/blastula and @meenakshi glue and stringr for automatic msg construction and sending

    In progress,

3. control for email response and automatically send next if no response
    * bcc mailgun api check if API can capture responses https://documentation.mailgun.com/en/latest/api_reference.html#api-reference + @lucas working on a method to capture responses, need - corpus 20 responses, classification (question, not interested, other), patterns
        * how to track replies http://blog.mailgun.com/tracking-replies-in-mailgun-or-any-other-email/  https://goo.gl/fT68xK
        * clicks: 

4. stretch goal: keep update + log (also to avoid duplicate msgs) + redflag https://docs.google.com/spreadsheets/d/1vtjRIbkjI5w9wRcYgtPo3CaiFuNSgHaOvwoxNpYKjrg/edit#gid=0<Paste> up to date so that we know what is going on behind the scenes
