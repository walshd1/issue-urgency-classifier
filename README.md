# Issue Urgency Classifier

Classifies new issues based on their description and labels, predicting their urgency level (e.g., critical, high, medium, low).

## Free
```yaml
- uses: walshd1/issue-urgency-classifier@v1
  with:
    gemini_api_key: ${{ secrets.GEMINI_API_KEY }}
```

## Paid (cost + 4.75%)
```yaml
- uses: walshd1/issue-urgency-classifier@v1
  with:
    service_token: ${{ secrets.ACTION_FACTORY_TOKEN }}
```
