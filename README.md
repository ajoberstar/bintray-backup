# org.ajoberstar bintray backup

This is a backup up of my Maven packages previously uploaded to Bintray/JCenter.

It's meant to provide a way for people to access old versions of any of my packages under the `org.ajoberstar` group that aren't on Maven Central.

> ![NOTE]
> As of 2025-09-01, `https://ajoberstar.org/bintray-backup/` redirects to `https://ajoberstar.github.io/bintray-backup/`. If you experience issues, please update your repo URL.
> 
> If you continue to experience issues, please send me an email (see my profile).

## Usage

From Gradle, specify the repository as:

```
maven {
  name = 'ajoberstar-backup'
  url = 'https://ajoberstar.github.io/bintray-backup/'
}
```
