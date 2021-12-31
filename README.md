

# UnsignedFlash



https://user-images.githubusercontent.com/1116555/147808516-57299f2f-2587-45d9-88a8-6daa0e221ea3.mp4



A vulnerability exists for some IC204 instrument clusters that are found in Mercedes-Benz vehicles of ~2007-2013, which enables flashing of arbitrary, unsigned firmware.

More details are [available in this document](https://raw.githubusercontent.com/jglim/UnsignedFlash/main/document_pub.pdf).


## Timeline:

```
10-06-21 : Notified Daimler of issue
11-06-21 : Received acknowledgement of the issue
22-06-21 : Received confirmation as known issue and closed as duplicate
22-06-21 : Request to disclose vulnerability
20-07-21 : Request from Daimler to redact a specific statement
28-07-21 : Revised document submitted for review
05-08-21 : Received OK from Daimler PR for disclosure
31-12-21 : Published disclosure
```


### Is there any safety impact?

There is **no immediate safety risk** to existing owners of MB vehicles equipped with an IC204 ECU. This is a flash-related vulnerability, therefore **physical access is required**.

### Is there a CVE to track the original vulnerability, along with this duplicate?

No (though I imagine that this issue might be present in other IC204 variants). No details were provided on the prior, original issue.

### Why is the report typeset in TeX?

It makes the vulnerability look more serious than it actually is.

### Are PoC files available?

No. The files are tangled with MB's IP (e.g. CBF, original firmware, modified demonstration CFF) which makes redistribution difficult. If you already have access to these, it should be possible to implement a proof-of-concept as the key parts of the vulnerability has been disclosed.

### How was the reporting process?

The security team was generally professional, courteous and technically competent. Initiating a report requires use of PGP which might be pretty off-putting for some folks. The team's handling of a duplicate issue was somewhat abrupt and has potential for improvement.

### Are you providing any support for the content here?

Unfortunately, no. Everything that I am able to share at this time is available here, and I am unable to provide additional support.
