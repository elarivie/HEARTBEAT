# Project's Vital Sign
*Guidelines about communicating project's health*

## Heartbeat

Every projects are started, improved and eventually die.  They are not a living being but at one point they inevitably are simply no more maintained at which point a project only has its momentum left.  It may be frustrating for users to discover a project at this stage and waste time on it without knowing that the project is unmaintained.

The purpose of the project's HEARTBEAT is therefore to provide a quick to consult vital sign which answers questions like:

*From a user point of view*
* Is the project alive?
* Is there a maintainer still around?
 * If I fill a bug report is there a chance that somebody will read it?
 * If I provide a pull request is there a chance that somebody will consider it?

If the answer to the previous questions is yes it certainly will motivate users to contribute to the project.  Else at least whey won't have wasted their time.

*From a maintainer point of view*
* When was the last time we looked at the project?
* Should we validate if the project still works today?

It therefore help to remind to dust off projects and to identify projects which should be deleted or at least advertised as dead projects.

### Requirement
 + ***REQ0000*** - SHALL be a file called *HEARTBEAT* without file extension.
 + ***REQ0001*** - SHALL be at the root of the project.
 + ***REQ0002*** - SHALL contains Unicode code point encoded with UTF-8.
 + ***REQ0003*** - SHALL contains a date in format YYYY-MM where Y's and M's are decimal digits [0, 1, 2, 3, 4, 5, 6, 7, 8, 9] and where an MM of 01 correspond to January.
 + ***REQ0004*** - SHALL have a file size of seven bytes.
 + ***REQ0005*** - SHALL never contains a date which represent a future moment.
 + ***REQ0006*** - SHALL be updated by a human (no automated task).
 + ***OPT0000*** - SHOULD when updated be set to the current year and month.

### Notes
 + The HEARTBEAT's date is truncated to a precision of months since having narrower precision is irrelevant for the need.

 + The HEARTBEAT is independent of project's changes or supported features list.  In fact it could pretty well be the only update being periodically perform on a given project.  It is important to understand that project's HEARTBEAT is unrelated to the project's VERSION.

 + It is not a requirement to update the HEARTBEAT every months.
