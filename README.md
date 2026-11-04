# Build jenkins job from Github Action :rocket:

This action builds/triggers a jenkins job, waiting it to be finished and enabling to pass job params.

## Inputs

### `curl-url`

## Example usage
```
    - name: "GET URL"
      uses: kerkenit/github-action-get@master
      with:
        curl-url: ${{ secrets.URL }}
```
