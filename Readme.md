# Buildkite Migration tool

**This project has been archived!**

This project provided a Ruby-based CLI command, as well as a web service, that could be used to translate CI pipelines to Buildkite from various other vendors. We have now replaced this approach with an AI/LLM-based solution. Using natural language prompts, this solution can convert a broader range of features and patterns that might be provided as input, and making targeted improvements is as simple as updating the prompts. As such, we are archiving this project and it will no longer be maintained.

Our LLM-based conversion tool can be accessed in the following ways:

* Using our Convert web app at [https://buildkite.com/resources/convert/](https://buildkite.com/resources/convert/).
* Using the [Buildkite CLI,](https://github.com/buildkite/cli) with its [pipeline convert command](https://buildkite.com/docs/platform/cli/reference/pipeline#convert-pipeline).
* Or, you can check out our [pipeline conversion rules](https://github.com/buildkite/conversion-rules) and use them with AI agents yourself.