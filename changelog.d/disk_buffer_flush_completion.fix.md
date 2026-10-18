Disk buffers now wait for asynchronous file writes to complete before reporting flushed
events, preventing readers from being notified before the written bytes are available.

authors: mojish
