---
layout: page
title: "For Conference/Workshop Organizers"
permalink: /organizers
---

ARR is a standalone centralized reviewing service designed to primarily support conferences and workshops under the umbrella of the Association for Computational Linguistics (ACL). Nonetheless, any other venue may choose to allow ARR-processed manuscripts (i.e., papers with ARR reviews and meta-reviews) to be committed for publication. 

Venues can generally subscribe to ARR in two different configurations: 

1. Full ARR -- only ARR-reviewed papers are allowed to be committed for publication at the venue (e.g., ACL 2022 and NAACL 2022).
2. Hybrid -- the venue has a separate reviewing process but also welcomes ARR-reviewed papers to be committed

"Full ARR" entails a closer collaboration between venue organizers and ARR, as ARR becomes the only path to publication for the venue (e.g., ARR makes an extra effort to make sure that all submissions targeting the venue are processed in time for venue commitment).
 
For "Hybrid" venues, ARR is mostly venue-agnostic. We will list such venues on our website and let ARR submissions that target the venue indicate this in the submission form (note that ARR does not need this information itself, we collect it merely to support the venues w.r.t. calculation of their acceptance rates).       

## Subscribing to ARR (Full or Hybrid)

Organizers of venues that would like to subscribe to ARR (either in Full or Hybrid setup) should make a pull request to [the ARR venues page](https://github.com/acl-org/aclrollingreview/blob/main/dates.md). They should update this file with the following information:

- Venue name and website
- Planned commitment deadline

## Commitment (fetching ARR Reviews)

Venue organizers need to decide the exact mechanism by which they will enable authors of ARR-processed papers to commit to their venue. OpenReview will then provide access to the all reviews of the committed papers. In principle, there are the following options: 

1. The venue uses OpenReview, receiving reviews from ARR only
    - In this case, the organizers should [submit a venue request form](https://openreview.net/group?id=OpenReview.net/Support) and inform the OpenReivew staff that they subscribe to ARR.
    - Once the commitment venue is deployed, there will be a field present in the submission form named "paper_link" for authors to commit their ARR processed papers. Here authors will simply provide the URL to the OpenReview forum of their ARR submission. This field is validated, so it will check whether the forum link exists in an ARR venue before allowing the author to submit.
    - For Full ARR venues, this commitment form is the only submission form to be created.

2. The venue uses OpenReview, with its own review process in OpenReview and reviews from ARR
    - In this case, submit two venue request forms, one for non-ARR reviewing and another for commitment of ARR-reviews papers.
    - OpenReview will provide read access to ARR forums of committed papers to the venue (assigned SACs, PCs) or import ARR reviews into the venue's OpenReview instance depending on the API used for the original ARR submission. Please contact OpenReview (<info@openreview.net>) when the submission deadline has passed and you're ready to begin the reviewing process.

3. The venue does not use OpenReview
	- In this case, the organizers need to figure out how to let the authors of ARR-reviewed papers indicate that they would like to commit to the venue
		- The authors need to provide a unique identifier of the ARR submission: the URL of the OpenReview forum of the ARR submission (https://openreview.net/forum?id=XXXXXXXXXXX)
	- The organizers send to ARR the list of committed papers (the list of URLs of OpenReview forums of committed papers)
	- ARR exports the reviews for committed papers and ships them to the venue organizers
	
## Setting Up an OpenReview Commitment Site

Once the OpenReview site is set up, the program chairs can navigate to the request form and click on the "Revision" Tab. It is suggested that organizers configure the site as pictured in [picture of OpenReview site with options checked for nonpublic anonymous submissions](/images/VenuesOR.PNG) and add the [additional submission options json](commitments.json).
These additional options include two requests for the paper PDF, one in camera-ready style (ie., with author names) and one that is anonymous, to enable a double-blind process for best paper selection.

## Duplicate Submissions

Venues subscribing to ARR as hybrid are encouraged to adopt the following wording: *A paper may not be simultaneously under review through ARR and YOUR_VENUE. A paper that has or will receive reviews through ARR may not be submitted for review to YOUR_VENUE.*

## Informing ARR of Decisions

ARR provides reviews, it does not make any acceptance or rejection decisions for the venues. ARR, however, forbids revisions to be submitted to ARR while the paper is under consideration (i.e., committed) for publication in a venue. Also, naturally, papers archived in venue's proceedings can no longer be revised and resubmitted to ARR. This is why, once the venue finalizes their program/proceedings, organizers are encouraged to send back to ARR the list of ARR-reviewed submissions that had been committed, with the indication on whether the paper is archived in venue's proceedings (papers accepted for non-archival participation in the venue, are not forbidden from resubmissions to ARR).   
 
