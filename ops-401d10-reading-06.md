# Reading 6

1. You have been made responsible for the company’s file server. How would you preserve the three elements of the CIA triad?

For confidentiality, I would ensure proper encryption methods for data at rest (disk-level/file-level encryption) and data in transit (FTPS/HTTPS, SSH/SFTP), and ensure proper authentication (2-factor). For integrity, I would use hash and digital signatures, each which would ensure the document/sender and receiver are all who need to access, and that nothing has been changed or modified thru transit.  For availability, I would set up a high availability cluster for file transfer.

2. Explain how hashing verifies data integrity using non-technical terms.

Hashing verifies data integrity by basically putting a stamp on the document, if the "stamp" at all changes, then it is not the same document and has been modified.

3. How is hashing and encryption different?

Hashing is more of a label denoted in the metadata, and encryption is actually changing the content (until the other person decrypts it and puts it back together).

## Things I want to know more about

all the hashes and encrytion methods.
