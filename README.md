# Health Value Pipelines
Health Value Pipelines are threads of value woven into the healthcare system by way of data processing and information creation, both by humans and intelligent automations, and by collaborations between the two.

# Whats that mean?
It might not seem like it but we are approaching a golden age of Healthcare IT, at least in the US.

### Forces at play
- At the macro level no matter what happens business models and value propositions are changing and will continue to change. Managed care, increased specialization and cost pressures are allowing smaller companies to enter the market in targeted niches and then seek to disrupt.
- 10+ years after the [HITECH Act](https://www.hipaajournal.com/what-is-the-hitech-act/) healthcare data is finally becoming readily available. There are government mandates for access by patients and for exchange among care providers. Its true that no two EHR's or healthsystems generate compatible datasets but the data is starting to flow nonetheless. 
- Healthcare data is *HUGE* and only getter huger with the incorporation of DNA, personal tracking data and social determinants of health.
- Over the last few years advances in machine learning have made significant new tools available for natural language processing, pattern recognition and computer aided decision making. Applying these tools to large healthcare data sets has the potential to significantly reduce care while simultaneously automating away work and reducing costs.
- The FHIR standard shows great potential to unify the world of the internet and mobile software with healthcare; and its success and adoption are encouraging further standardization efforts (eg [mCODE](https://mcodeinitiative.org/)?)

# Health Pipelines
Health Pipelines is the name I'm giving to the notion of processing pipelines at multiple levels of abstraction for health care data and services.

### Processing Pipelines
In modern large-scale software development there is significant adoption of data processing pipelines. Deriving from earlier scaling methodologies like [MapReduce](https://en.wikipedia.org/wiki/MapReduce) these are queue and event based architectures that handle huge flows of information in realtime - think Facebook servers processing an incoming click stream through layers of storage, aggregation, processing and data mining.

### Health Data Pipelines
Health data pipelines handle streams of events like patient admit, discharge or transfer information; order queues and result feeds; referrals and appointments; and many other data flows. Healthcare systems are very heterogeneous at all levels of the communications stack so basic connectivity, ingestion and data normalization are challenging if starting from scratch.

### Health Information Pipelines
Building on Data Pipelines, Health Information Pipelines process the raw data to derive healthcare information. These are normalized, time sequenced, de-duplicated items of interest in the provisioning of healthcare.

### Health Value Pipelines
Building on Information Pipelines, Health Value Pipelines provide a full end to end thread of healthcare value-add. Threads might include
- Tracking a prescription order, reminding the patient if it's not picked up, and notifying care team members of progress.
- Getting patient approval, uploading a chart, evaluating the patient against applicable on-going trials, summarizing chart contents and trial options, and passing that information to a review panel.

# The Human in the Loop
Health care is an intrinsically human to human activity. Whats more human than caring for others?

# The Computer in the Loop
Healthcare is a data-rich environment. New ML tools change the equation on what only-humans can do.

# The Mission
Work with companies that are improving patient care (like [Navya](https://navya.care/)) or reducing societal healthcare cost (like someone else) to improve their health value pipelines by building and commoditizing software components that allow humans and computers to more efficiently and empathetically provide healthcare services.
