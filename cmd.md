# Explore Generative AI with the Gemini API in Agent Platform: Challenge Lab || **GSP515**

**Command:**

```bash
curl -X POST \
-H "Authorization: Bearer $(gcloud auth print-access-token)" \
-H "Content-Type: application/json" \
"https://${API_ENDPOINT}/v1/projects/${PROJECT_ID}/locations/${LOCATION}/publishers/google/models/${MODEL_ID}:generateContent" \
-d '{
  "contents": [{
    "role": "user",
    "parts": [{"text": "Why is the sky blue?"}]
  }]
}'
```

```bash
gs://github-repo/img/gemini/multimodality_usecases_overview/mediterraneansea.mp4
```
