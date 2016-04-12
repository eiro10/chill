# Chill-rs Change Log

## v0.1.1 (unreleased)

### New

* New action type to execute a view (`action::ExecuteView`).
* New support for creating, reading, updating, and deleting attachments
  as part of a document. Still no support for accessing attachments on
  the CouchDB server separately from a document.
* New test type to mock view responses (`testing::ViewResponseBuilder`).

## v0.1.0 (2016-03-26)

This is the first release. It has minimal support for creating, reading,
updating, and deleting documents.