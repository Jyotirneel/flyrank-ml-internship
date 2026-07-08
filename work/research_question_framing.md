# Research Question Framing. ML-02

## Lane

**Lane 4: CTR / Engagement Opportunity Scoring** (Core lane)

## Research Question

We want to find out which pages are not getting many clicks as they should based on where they appear. We also want to know if this happens more with types of content.

This is based on something we found in Week 1: when a page gets at 100 impressions over 90 days the click-through rate is usually pretty normal between 0 and 0.36.. We saw that feedly article pages on the first page had a really high click-through rate of 0.90, which is much higher than expected. This could mean that people really like this type of content or there might be a problem with how we're tracking clicks. Either way we need to look into this before we can trust the click-through rate to tell us what to prioritize.

## Unit of Analysis

We will look at each page as an item and score it based on how it has been doing lately including how many people have seen it clicked on it, where it appears, what type of content it is and how old it is.

## Output

We will make a list of pages that have a click-through rate that is much lower than expected or much higher than expected like the feedly article pages. We will also include a reason why each page's on the list.

## Action Someone Could Take

For pages that are not doing well someone could try rewriting the title or meta description to make it more appealing. For the article pages that have a really high click-through rate we should check to make sure our data is accurate before we use it to decide what to prioritize.

## Cost of a Wrong Recommendation

If we wrongly think a page is not doing well we will waste time trying to fix it. If we miss a page that is really not doing well it will keep losing clicks that it could be getting.. If we use bad data to decide what to prioritize we might end up focusing on the wrong things.

## Why This Isn't Train a Model"

The problem is that we need to figure out what a normal click-through rate is for each type of content and where it appears. This means we need to set a baseline look at the differences and make sure we have data to be accurate. If we just train a model on the click-through rate without doing this it will learn from mistakes in the data of real information. We need to use judgment to decide what is important and what is not.

## Language Discipline

We will only report what we find and not try to say why it is happening. We will not mention any client names, websites or search terms, in our report.
