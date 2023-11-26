+++
title = "My second post"
date = 2019-11-28
[taxonomies]
tags=["DataEngineering"]
+++

This is my second blog post.

It has some python code

```python
@asset
def test_asset(context: OpExecutionContext):
    context.log.info("Hello")
    return 1

```
