# hawkBit Migration Guides
## Release 0.2
### Configuration Property changes
- hawkbit.server.controller._ have changed to hawkbit.server.ddi._
- info.build._ have changed to hawkbit.server.build._
- hawkbit.server.demo._ have changed to hawkbit.server.ui.demo._
- hawkbit.server.email.support has changed to hawkbit.server.ui.links.support
- hawkbit.server.email.request.account has changed to hawkbit.server.ui.links.requestAccount
- hawkbit.server.im.login.url has changed to hawkbit.server.ui.links.userManagement

### REST API model changes for clients
- ENTITYPagedList classes have been removed; generic PagedList used instead (e.g. PagedList<TargetRest> instead of TargetPagedList).
- ENTITYsrest classes have been removed; List<ENTITYrest> used instead (e.g. List<TargetRest> instead of TargetsRest)