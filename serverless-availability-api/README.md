# Working with Serverless Framework and AWS

## Notes

**CLI Commands:**
- ``serverless deploy --stage dev``
- ``serverless deploy --stage prod``
- ``serverless remove --stage dev``
- ``serverless remove --stage prod``
- ``serverless invoke --stage dev --function getSingleListing``

## ToDo's

- [ ] When a user opens a Merge Request on GitHub:
  - [ ] Create new feature environment when a user creates a merge request (branch name + commit hash)
    - [ ] When a user merges the Merge Request
      - [ ] Deploy the API to the production stage
      - [ ] Remove the feature environment
