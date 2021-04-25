# org.ajoberstar bintray backup

This is a backup up of my Maven packages previously uploaded to Bintray/JCenter.

It's meant to provide a way for people to access old versions of any of my packages under the `org.ajoberstar` group that aren't on Maven Central.

## Usage

From Gradle, specify the repository as:

```
maven {
  name = 'ajoberstar-backup'
  url = 'https://ajoberstar.org/bintray-backup/'
}
```
