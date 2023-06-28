$GITHUB_USER="RSteeno"
$GITHUB_REPO="flux2-multi-tenancy"

flux bootstrap github `
    --owner=$GITHUB_USER `
    --repository=$GITHUB_REPO `
    --branch=main `
    --personal `
    --path=clusters/staging