# talentdatabase
{
  "query": {
    "bool": {
      "must": [
        {
          "match": {
            "language": "Hindi"
          }
        },
        {
          "match": {
            "profession": "Doctor"
          }
        }
      ]
    }
  }
}
