<!--

If you are not familiar with this template, you can switch to the `preview` tab to consult the footnotes for more information on how to fill it out and more.

- Depending on the selections, the corresponding labels will be automatically added when you create/edite your pull request.

- At the creation of the pull request, tests are also conducted:

  - Check if title contains only ASCII printable characters
  - The presence of a description.
  - If you have selected: `This pull-request shouldn't be merged before`, verification of the date format and that it is indeed in the future.

According to the results, a comment will inform you of what you need to correct.

- If you selected: `Other tool (specify which tool was used)`, please specify the tool(s) used by replacing `(specify which tool was used)`.
- About `Merge date option` only one is allowed as about `priority` 

Remember that to check a box, replace `- [ ]` with `- [x]` without any spaces around the `x`

-->

## What type of pull-request is this?

- [ ] New guide(s) [^NEW_GUIDE]
- [ ] Update of existing guide(s)
- [ ] Minor update of existing guide(s)
- [ ] Fix
- [ ] Optimization
- [ ] Index categories update
- [ ] Deletion of guide(s) [^GUIDE_DELETION] 

## Description [^DESCRIPTION]



## Mandatory information

### The translations in this pull-request have been done using

- [ ] OVHcloud integrated translation LLM [^LLM]
- [ ] Systran
- [ ] Other tool (specify which tool was used) [^TRANSLATION_OTHER_TOOL]
- [ ] None, except my own mad brain of course...

__or__

- [ ] This pull-request didn't require any translation

### Merge date option

- [ ] This pull-request can be merged as soon as possible
- [ ] This pull-request shouldn't be merged before: __YYYY-MM-DD__ [^MERGE_DATE]

### US replication

- [ ] This pull-request content should be replicated for the [US OVHcloud documentation](https://support.us.ovhcloud.com/hc/en-us) [^US_REPLICATE]

## Other information

### Select the priority for this pull-request [^PRIORITIES]

- [ ] Priority Urgent
- [ ] Priority High
- [ ] Priority Low
- [ ] Priority Dependency

[^NEW_GUIDE]: You need to create a __`meta.yaml`__ file with at least the __`id`__ _(uuid v4)_ and __`full_slug`__ _([a-z0-9-])_ keys filled in, and edit the index: https://github.com/ovh/docs/blob/develop/pages/index.md.
    Example:
    ```yaml
    id: 2a9eb7ad-bf80-4049-a323-021849f37973
    full_slug: this-is-my-full-slug-for-guide-01
    ```

[^GUIDE_DELETION]: Redirections may be needed, contact the OVHcloud Guides Team.
[^DESCRIPTION]: Please provide a short description for your pull-request, including (if applicable) a ticket reference (no internal URL!) or GitHub issue
[^LLM]: If you're interested in this new option, contact the Guides team
[^TRANSLATION_OTHER_TOOL]: Please specify the tool(s) used by replacing __`(specify which tool was used)`__.
[^MERGE_DATE]: Replace it with a real date.
[^US_REPLICATE]: If you know about it, please select it else just ignore it.
[^PRIORITIES]: Definition of priorities:
    &bull; __Urgent__: _This pull-request contains urgent updates or fixes._  
    &bull; __High__: _This pull-request contains high-priority elements._  
    &bull; __Low__: _This pull-request contains documentation which has no critical aspect._  
    &bull; __Dependency__: _This pull-request contains documentation for an upcoming product or feature_<br>
