

# push a image to Github packages
1. Create image
2. Create PAT(Personal Access Token) on Github
3. Authenticate GHCR
4. Tag and push our image to GHCR


'''
export CR_PAT=<TOKEN>
echo $CR_PAT | docker login ghcr.io -u USERNAME --password-stdin

echo "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" | docker login ghcr.io -u 22211a7262-png --password-stdin

'''
# Use Github actions to publish a Docker image to Github packages
