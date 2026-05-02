# Salesforce Einstein APIs (salesforce-einstein)
Collection of Salesforce Einstein AI and machine learning APIs for predictive analytics, natural language processing, computer vision, generative AI, and intelligent automation.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/salesforce-einstein/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Artificial Intelligence, Computer Vision, CRM, Machine Learning, Natural Language Processing, Predictive Analytics, Salesforce

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-02

## APIs

### Einstein Vision API
Image recognition and classification API for building custom AI-powered image recognition models.

**Human URL:** https://www.salesforce.com/products/einstein/ai-deep-dive/image-recognition/

#### Tags
- Computer Vision, Image Recognition, Machine Learning

#### Properties
- [Documentation](https://metamind.readme.io/docs/intro-to-einstein-vision)
- [OpenAPI](openapi/salesforce-einstein-vision-openapi.yml)

---

### Einstein Language API
Natural language processing API for sentiment analysis, intent detection, and text classification.

**Human URL:** https://www.salesforce.com/products/einstein/ai-deep-dive/natural-language-processing/

#### Tags
- Machine Learning, Natural Language Processing, Sentiment Analysis, Text Classification

#### Properties
- [Documentation](https://metamind.readme.io/docs/intro-to-einstein-language)
- [OpenAPI](openapi/salesforce-einstein-language-openapi.yml)

---

### Einstein Prediction Builder API
Create custom AI predictions on Salesforce data without code using Einstein AI.

**Human URL:** https://help.salesforce.com/s/articleView?id=sf.einstein_prediction_builder.htm

#### Properties
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/einstein_prediction_builder.htm)
- [OpenAPI](openapi/salesforce-einstein-prediction-builder-openapi.yml)

---

### Einstein Discovery API
Advanced analytics and automated insights API for predicting outcomes and recommending actions.

**Human URL:** https://www.salesforce.com/products/einstein/features/

#### Properties
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/)
- [OpenAPI](openapi/salesforce-einstein-discovery-openapi.yml)

---

### Einstein Bots API
Conversational AI API for building intelligent chatbots and virtual assistants.

**Human URL:** https://www.salesforce.com/products/service-cloud/features/chatbots/

#### Properties
- [Documentation](https://developer.salesforce.com/docs/service/einstein-bots/guide/einstein-bots-developer-overview.html)
- [OpenAPI](openapi/salesforce-einstein-bots-openapi.yml)

---

### Einstein GPT API
Generative AI API for creating personalized content across Salesforce using LLMs.

**Human URL:** https://www.salesforce.com/einstein-gpt/

#### Properties
- [Documentation](https://developer.salesforce.com/docs/einstein/genai/overview)
- [OpenAPI](openapi/salesforce-einstein-gpt-openapi.yml)

---

## Capabilities

### Shared Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/einstein-vision.yaml](capabilities/shared/einstein-vision.yaml) | Shared definition for Einstein Vision API |
| [capabilities/shared/einstein-language.yaml](capabilities/shared/einstein-language.yaml) | Shared definition for Einstein Language API |
| [capabilities/shared/einstein-gpt.yaml](capabilities/shared/einstein-gpt.yaml) | Shared definition for Einstein GPT API |
| [capabilities/shared/einstein-bots.yaml](capabilities/shared/einstein-bots.yaml) | Shared definition for Einstein Bots API |
| [capabilities/shared/einstein-prediction-builder.yaml](capabilities/shared/einstein-prediction-builder.yaml) | Shared definition for Einstein Prediction Builder API |
| [capabilities/shared/einstein-discovery.yaml](capabilities/shared/einstein-discovery.yaml) | Shared definition for Einstein Discovery API |

### Workflow Capabilities

| File | Description | APIs |
|------|-------------|------|
| [capabilities/ai-analytics.yaml](capabilities/ai-analytics.yaml) | AI analytics (vision + language) | Einstein Vision, Einstein Language |
| [capabilities/generative-ai.yaml](capabilities/generative-ai.yaml) | Generative and conversational AI | Einstein GPT, Einstein Bots |
| [capabilities/predictive-intelligence.yaml](capabilities/predictive-intelligence.yaml) | Predictive intelligence and analytics | Einstein Prediction Builder, Einstein Discovery |

## Artifacts

| Artifact | Path |
|----------|------|
| OpenAPI (Vision) | [openapi/salesforce-einstein-vision-openapi.yml](openapi/salesforce-einstein-vision-openapi.yml) |
| OpenAPI (Language) | [openapi/salesforce-einstein-language-openapi.yml](openapi/salesforce-einstein-language-openapi.yml) |
| OpenAPI (GPT) | [openapi/salesforce-einstein-gpt-openapi.yml](openapi/salesforce-einstein-gpt-openapi.yml) |
| OpenAPI (Bots) | [openapi/salesforce-einstein-bots-openapi.yml](openapi/salesforce-einstein-bots-openapi.yml) |
| OpenAPI (Prediction Builder) | [openapi/salesforce-einstein-prediction-builder-openapi.yml](openapi/salesforce-einstein-prediction-builder-openapi.yml) |
| OpenAPI (Discovery) | [openapi/salesforce-einstein-discovery-openapi.yml](openapi/salesforce-einstein-discovery-openapi.yml) |
| JSON Schema (Prediction) | [json-schema/salesforce-einstein-prediction-schema.json](json-schema/salesforce-einstein-prediction-schema.json) |
| JSON Schema (Dataset) | [json-schema/salesforce-einstein-dataset-schema.json](json-schema/salesforce-einstein-dataset-schema.json) |
| JSON Schema (Model) | [json-schema/salesforce-einstein-model-schema.json](json-schema/salesforce-einstein-model-schema.json) |
| JSON Schema (Bot Session) | [json-schema/salesforce-einstein-bot-session-schema.json](json-schema/salesforce-einstein-bot-session-schema.json) |
| JSON Schema (Generation) | [json-schema/salesforce-einstein-generation-schema.json](json-schema/salesforce-einstein-generation-schema.json) |
| JSON-LD Context | [json-ld/salesforce-einstein-context.jsonld](json-ld/salesforce-einstein-context.jsonld) |
| JSON Structure | [json-structure/salesforce-einstein-structure.json](json-structure/salesforce-einstein-structure.json) |
| Spectral Rules | [rules/salesforce-einstein-rules.yml](rules/salesforce-einstein-rules.yml) |
| Vocabulary | [vocabulary/salesforce-einstein-vocabulary.yml](vocabulary/salesforce-einstein-vocabulary.yml) |

## Examples

- [Classify Image](examples/salesforce-einstein-classify-image-example.json)
- [Generate Content from Prompt Template](examples/salesforce-einstein-generate-content-example.json)

## Common Properties

- [Developer Portal](https://developer.salesforce.com/)
- [Getting Started](https://developer.salesforce.com/developer-centers/einstein)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm)
- [Terms of Service](https://www.salesforce.com/company/legal/agreements/)
- [Privacy Policy](https://www.salesforce.com/company/privacy/)
- [Status](https://status.salesforce.com/)
- [Support](https://help.salesforce.com/)
- [Blog](https://developer.salesforce.com/blogs)
- [Community](https://trailhead.salesforce.com/community)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
