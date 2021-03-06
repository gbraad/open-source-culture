Open Source way
===============


Reference material
------------------
    
  * Online material: http://www.theopensourceway.org/book/The_Open_Source_Way-Stuff_everyone_knows_and_forgets_anyway.html
  * Online material: http://catb.org/~esr/faqs/smart-questions.html
  * Online material: https://wiki.openstack.org/wiki/How_To_Contribute
  * Online material: http://fedoraproject.org/wiki/Staying_close_to_upstream_projects
  * Book: Pro Git https://git-scm.com/book/zh/v2 (ebook available)


Outline
-------


### Understand the Open Source way
  * history
  * it is not software (only, but a philosophy)
  * difference between free vs open
  * concept of sharing
    * origins and motivation
    * us and we  vs.  I and them
    * (cathedral and bazaar)
  * why
    * successful projects
      * created for a purpose
      * just came about
    * How did the Internet come about
      * LAMP - stack
        * php became common
        * easy to use
          * compare to still currently how to deploy Ruby or Python
            * we need a PaaS ?!???
  * advantages
    * myths: http://www.zdnet.com/article/six-open-source-security-myths-debunked-and-eight-real-challenges-to-consider/
  * disadvantages
  * upstream  
    * http://fedoraproject.org/wiki/Staying_close_to_upstream_projects


### What is Open Source
  * https://opensource.com/resources/what-open-source
  * http://www.theopensourceway.org/book/The_Open_Source_Way-Stuff_everyone_knows_and_forgets_anyway.html
  * http://teachingopensource.org/
  * http://www.slideshare.net/ganglia/teaching-opensource-2015
  * https://en.wikipedia.org/wiki/History_of_free_and_open-source_software
  * https://en.wikipedia.org/wiki/Open-source_software


### Cultural challenges
http://www.slideshare.net/amandalam/collaborative-product-development-in-foss-projects

  * Cultural differences
  * Geert Hofstede's Cultural dimensions
    
Cultural Insights

  * http://geerthofstede.nl/
  * http://geert-hofstede.com/
    
Asian cultures are vastly different from Western cultures
Even within Asia countries have different cultural characteristics


#### Cultural Dimensions


#### Organisational culture


### Comparing communities
  * compare to Ceph
  * compare to javaScript community


### Understand OpenStack as a community
  * foundation mission
    * core values
    * target audience
  * target audience
    * enterprise need
      * consultant needs to listen
        * brdige gap between community
          * task of the engineer


### Dealing with issues
  * bug reporting
  * example
    * openoffice
    * mozilla
    * bugzilla
  * bug verification

  * http://www.informit.com/articles/article.aspx?p=1994799
  * http://www.openoffice.org/qa/issue_handling/bug_writing_guidelines.html
  * http://www.openoffice.org/qa/issue_handling/basic_rules.html


#### Who will read ?
  * Can be people in different roles
    * Users: operations, 
    * Engineers: developers
    * any person, or a combination of them.
  * community members who performe triage on defects
  * developers who finally fix the defect
  * QA engineer(s) who needs to verify the fix
  * everybody who has the same problem and tries to understand whether
    * your defect also describes his/her problem.
    * or whether your issue is one they like to vote for
  * possibly a user experience team member evaluating a feature request
  * possibly a release team member evaluating whether the defect is important enough to be included in some maintenance update.


### Asking questions
  * the smart way
  * Show you have done your homework

http://catb.org/~esr/faqs/smart-questions.html

When you ask a question, you are asking people to do you a favor. People have no reason to help you, but in general hackers (aka programmers) will happily do so provided you:
  * show that you've done your homework,
  * ask nicely, and
  * make it easy for them to understand what you need.

http://c2.com/cgi/wiki?HowToAskQuestionsTheSmartWay


### How to get involved
  * "Do good things and talk about it"
    * documentation
    * presentation
  * attribution (you, company) ?
  * code contributions
    * when (roadmap)
      * incremental
    * break up in features / functions (incremental)
      * progress tracking
  * code reviews
    * internal (informal)
    * external (gated)
    * first offer passing / failing tests ?
  * mailinglists
    * email guidelines
      * Pragmatic programmer
        * no-html markup
  * ...


### Why we do certain things in a certain way
  * code reviews
    * law of triviality / paint the bikeshed
  * unit tests
    * TDD principles
    * example
  * mailinglists
  * IRC
  * etc.


### Do's and don'ts
  * don't: private discussions
  * do: bug triage
  * don't: be poisonous
  * do: code review
  * Online material: http://producingoss.com/en/setting-tone.html 


### Contributing code
  * things you should do before pushing your code
  * coding style (such as pep8)
  * unit tests
    * indirect (gated)
    * direct
  * https://wiki.openstack.org/wiki/How_To_Contribute
  * http://docs.openstack.org/infra/manual/developers.html#development-workflow


### Understand the tools you use
  * your editor
    * but always good to know Vi
  * git
    * branching, merging (rebasing)
    * review process
  * expected skills
    * English language???


## Advanced topic (not sure if to include)
Although much of this would refer to former topics anyway.

  * How to build a community ?
    * how to get people involved ?
      * make it easy to join

http://producingoss.com/


### Email guidelines
  * Inline replying
  * How to handle attachments
  * Information is best consumed if provided in a simple format (index)
  * No HTML format


### Git usage
  * Work on a topic branch
  * Understand rebasing
  * Git review


### Local developer environment
  * DevStack setup
  * PackStack setup


### What makes F/OSS projects more difficult to manage?
  * Often involve global virtual teams
    * Cultural differences
  * Uneven distribution of skill sets (especially in smaller projects)
    * Too developer-dominated, too technical-focused
  * Gender bias and stereotypes
    * Male-dominated
    * Female-unfriendly environment
  * Knowledge-sharing challenges
    * Lack of informal socialisation
    * weak team climate
    * lack of trust and respect
