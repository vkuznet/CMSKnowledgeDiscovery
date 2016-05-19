# CMSKnowledgeDiscovery

## Actions

Valentin:
- Collect set of questions for the project, e.g. How to run XYZ analysis
- Break it down into sub-questions:
  - how to run/submit a grid job in CMS
  - how to find data X, Y, Z for my analysis, e.g. find files for given run
  - how to find configuration files for my analysis, e.g. which Pythia
    configuration files were used for dataset /a/b/c
  - how to generate MonteCarlo for my process
  - where I can submit my job
  - which release should I use
  - which samples are available for XYZ analysis
  - which tuples are available for XYZ analysis
  - do I need to run my analysis on RAW, RECO, AOD sample
  - what is a description of tuple X
  - how I can monitor my job
  - where is my job

- Collect real question from CMS hypernews
  - I met the following problem while submitting crab job
    ... description of the problem ...
    - missing library
    - missing dependency
    - missing files/block/dataset (data issue)
    - my job failed with ExitCode: 123
    - received HTTP error from CMS data-service
    - can't access published dataset
  - software related questions
    - how to run CMSSW on OSX, Ubuntu, etc.
    - problem with a release X_Y_Z
    - use SL5 on SL6, etc.
    - 

  - service oriented questions
    - authentication problem (expired certificate, unable to access SiteDB,
      etc.)
    - how to convert X to edm::YYY
    - segmentation violation
    - Num of input events for and EDM file
    - access miniAOD filter results from DQM modules in the same step

  - physics questions
    - find Higgs cross sections at 13 TeV
    - Luminosity recommendation for 2015 analyses
    - recommendation for NLO ttV xsecs at 13 TeV 
    - Signal samples for ICHEP
    - Retrieving prescales in 80X

- Outline available data sources for the system
  - CMS twiki
  - github repositories
  - github wiki
  - CMS data-services, e.g. DBS, PhEDEx, McM, RequestManager, Dashboard, DAS
  - CMS hypernews
