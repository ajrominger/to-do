# code
- get random number functions faster in *pika*, means making q fun in C++
- get *pika* working with *meteR*---to do so requires uploading pika to CRAN, then making meteR depend on it
- make *meteR* spatial stuff use spatial packages
- fix axis function in *socorro* to:
    - take different tranform funs
    - not over-populate axis when limits are huge (e.g. 4 ords of mag)
    - take a vector more than 1 long for the `side` argument (e.g. allowing simultaneous axis addition)
- play around with eBird (and other cit sci) R packages
- play with colorspace


# sadScaling

# paleo sstat

# happySAD
- figure out when z-val is informative (i.e. what sample size)
- test z-val to make sure the analytical version is really right 
    - see if *pika* logLikZ works when 'by hand' z from sadScaling does not
- test out different metrics like ks and mse (again!)
- figure out sample size to reject given SAD model when we don't know the true model (i.e. can't use deltaAIC of true model v. alternative model)
- make outline of concepts for the paper
    - different models of SADs have been explored so we won't re-hash that, but we will categorize into lognorm and gamma
    - lognormal vs. gamma have interesting dirivations that deserve more attention
    - analyses
        - when can lognorm and gamma be differentiated?
        - when and how to use the exact test
            - power and sample size in S and N
        - best metrics for goodness of fit
            - compare across SAD shapes, N, S:
                - ks
                - mse on cdf
                - mse on rad (log and linear scale)
                - logLikZ
                - kl distance
        - subsampling and the veil-line
            - random sampling v. clustered sampling
            - more on that soon...


# isingEcology
- make scaling routine use all matrix methods
- read up

# eco-evo meeting

# mol2ecol
- review comments
- tighten up intro
- better motivate proposed tests
- plan a meeting
- design a simulation

# warbler
- look at trait values in sympatry v. allopatry
- write danny for more data

# website 
- get research page to show recent projects determined from github
    - do the website code
- update cv to be both html (need css?) and pdf
    - https://mszep.github.io/pandoc_resume/
    - http://elipapa.github.io/markdown-cv/
    - http://blm.io/blog/markdown-academic-cv/
    - https://github.com/there4/markdown-resume
    - http://svmiller.com/blog/2016/03/svm-r-markdown-cv/
    - https://bitlyfied.com/2013/03/14/markdown-cv/
- make publications list (ideally dynamically)

# logistic
- make meteR presentation
- nsf review
- format to-do
    - make bash script that:
        1. commits changes to git
        2. figures out updates using diff
        3. formats new list with accomplishments crossed off

# edward

# meetings

# reading
- look at sid's presentation
- look at john's grant
- read this: https://arxiv.org/pdf/1608.08995.pdf
- look into eric smith stuff: http://tuvalu.santafe.edu/~desmith/Publications.html
- look at pablo's book chapter
- large deviations: https://arxiv.org/pdf/0804.0327.pdf
- mirta's grant

