- module level logger with `getLogger(__name__)`
-
- ## hierarchical logging
	- Logged messages to the module-level logger get forwarded to handlers of loggers in higher-level modules, all the way up to the highest-level logger known as the root logger; this approach is known as