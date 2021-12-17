# design-language-system

- Get Me ( Check Token and get User Profile )

```sh
  curl --location --request GET 'https://api.github.com/user' \
  --header 'Authorization: Bearer {{PERSONAL_ACCESS_TOKEN}}'
```

- Get List Artifact :

```sh
  curl --location --request GET 'https://api.github.com/repos/mghozyn/design-language-system/actions/artifacts' \
--header 'Authorization: Bearer {{PERSONAL_ACCESS_TOKEN}}' \
```

- To Download Github Artifact, run curl script in terminal :

```sh
  curl \
    -vLJO -H "Authorization: Bearer {{PERSONAL_ACCESS_TOKEN}}" \
    https://api.github.com/repos/mghozyn/design-language-system/actions/artifacts/{{ARTIFACT_ID}}/zip
```

More API from Github :
https://docs.github.com/en/rest/reference/actions#artifacts

Test Commit
