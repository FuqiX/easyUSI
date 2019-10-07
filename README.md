### Prerequest:
an explore aap account
### example
```sh
./USI_submission.py -u myName -t myteam -n -sp examples/sample.txt
```
### Note!
1. only support samples for now.
2. data must follow USI schema

### Features to add
1. Support adding other users to the team.
2. Start timer after getting the second token to make sure no 'time out' The default token is valid for 1 hour. It's possible to request a 3 hour token on the USI website.
3. Scalable submission. (maybe a bash script to support 1000 samples)
4. Link assay to the study it belongs automaticlly instead of listing the studyRef in the files (how to make sure the 'alias' is shared in the same file)
5. Check what would happen if taxonId and taxon name do not match. (DONE, sample status 201, validation status 200, taxon validation: ERROR)
6. whats the difference between projects and studies in ENA
7. "statusName_Not submittable/status" until validation checkout.
8. "processStatus" might take a long time
9. ENA supports more data file types than USI
10. Return accession ID for future reference, probably an output file
11. in dev, the data is removed 2 months after the most recent touch.
12. 

