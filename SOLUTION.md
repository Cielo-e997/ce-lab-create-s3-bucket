# S3 Bucket Lab

## Bucket Information

Bucket name: cielo-demo-2026  
Region: eu-central-1  

---

## Objects Uploaded

Multiple objects were uploaded including:

- README.txt (text file)
- resume.pdf (document)
- logo.jpg (image)
- cli-test.txt (CLI upload)
- version-test.txt (versioning test)

Folders created:

- images/
- documents/
- backups/
- project/

---

## Storage Classes

The following storage classes were used:

- Standard
- Standard-IA
- Intelligent-Tiering

---

## Versioning

Versioning was enabled on the bucket.

A file (version-test.txt) was uploaded twice with different content, and multiple versions were successfully created.

---

## Encryption

Default encryption was enabled using:

- SSE-S3 (Amazon S3 managed keys)

---

## Tags

The following tags were added:

- Environment: Development
- Project: Bootcamp

---

## CLI Operations

The following CLI operations were performed:

- Uploading files to S3
- Listing bucket contents
- Downloading objects
- Deleting objects
- Syncing local directories with S3

All CLI outputs are documented in cli-outputs.txt