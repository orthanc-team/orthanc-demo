## What is this repository for?

Orthanc deployment demo/test

## Secret files

For obvious security reasons, secret files shall not be included in the repo.  Here is the directory strucutre of these files:

```
secrets
- ORTHANC__AUTHORIZATION__WEB_SERVICE_PASSWORD
- orthanc-token.secret.env
- SECRET_KEY
- KEYCLOAK_CLIENT_SECRET
- meddream.secret.env
- orthanc-api.secret.json
- KC_BOOTSTRAP_ADMIN_PASSWORD.env
```

And sample contents

### ORTHANC__AUTHORIZATION__WEB_SERVICE_PASSWORD

```
change-me-auth-service-pwd
```

### orthanc-token.secret.env

```
USERS={"share-user":"change-me-auth-service-pwd"}
```

### SECRET_KEY

```
change-me-I-m-a-secret-key
```

### KEYCLOAK_CLIENT_SECRET

This is obtained from the Keycloak startup logs
```
abcDEF...
```

### meddream.secret.env

```
ORTHANC_PWD: "change-me-meddream-pwd"
```

### KC_BOOTSTRAP_ADMIN_PASSWORD.env

```
KC_BOOTSTRAP_ADMIN_PASSWORD=change-me-keycloak-init-pwd
```
