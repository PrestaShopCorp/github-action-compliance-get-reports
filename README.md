# github-action-compliance-get-reports
Get reports of a scan when reports is generated

```
compliance-get-reports:
    name: get reports
    runs-on: ubuntu-latest
    steps:
        - name: get reports from compliance
          uses: PrestaShopCorp/github-action-compliance-get-reports@v1.0
          with:
            version: 
            technicalName: 
            token-uri: ${{ secrets.OAUTH_TOKEN_URI }}             
            cookie: ${{ secrets.OAUTH_COOKIE }}                 
            client-id: ${{ secrets.OAUTH_CLIENT_ID }}                  
            client-secret: ${{ secrets.OAUTH_CLIENT_SECRET }}                 
            grant-type: ${{ secrets.OAUTH_GRANT_TYPE }}                  
            audience: ${{ secrets.OAUTH_AUDIENCE }}                   
            scope: ${{ secrets.OAUTH_SCOPE }}                  
            compliance-base-uri: ${{ secrets.COMPLIANCE_BASE_URI }}  
            pat: ${{ secrets.PAT }} 
```