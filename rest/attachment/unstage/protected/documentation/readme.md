Originally introduced to allow for gallery level manipulation in the frontend without having a custom wrapper object and thus custom REST services for updating.

However, it quickly became evident that the list of attachments being manipulated in the frontend is not limited to staged objects (e.g. during update) so a mix needs to be supported.
The service "finalize" was added. This allows both unstaging of attachments, DELETING of attachments that are not in that list and updating metdata.