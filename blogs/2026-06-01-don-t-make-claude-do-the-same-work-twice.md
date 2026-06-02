---
title: "Don't make Claude do the same work twice"
url: "https://www.zenml.io/blog/claude-agent-sdk-durable-runtime"
date: "2026-06-01"
feed_url: "https://www.zenml.io/blog/rss.xml"
---
Claude Agent SDK runs the agent loop. Kitaru adds the durable runtime around a completed invocation — checkpointed results, artifacts, replay boundaries, and waits.
