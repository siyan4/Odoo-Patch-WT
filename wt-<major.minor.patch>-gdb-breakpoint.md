/usr/include/boost/asio/detail/impl/socket_ops.ipp:690:  int result = ::listen(s, backlog);
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/Wt/WIOService.C:90:    for (int i = 0; i < impl_->threadCount_; ++i) {
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/Wt/WIOService.C:184:  initializeThread();
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/Wt/WServer.C:407:    int rc, sig= -1;
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/Wt/WServer.C:410:    rc= sigwait(&wait_mask, &sig);
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/Wt/WServer.C:413:    switch (rc) {
  
/usr/include/boost/asio/detail/impl/scheduler.ipp:453:  while (!stopped_)
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/web/WebController.C:616:  if (!running_) {
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/web/WebController.C:842:      session->handleRequest(handler);
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/web/WebSession.C:1289:  WebRequest& request = *handler.request();
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/web/WebSession.C:3120:  if (!s)
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/Wt/WTextArea.h:83:  const WT_USTRING& text() const { return content_; }
/home/sib/Projects/wt-4.11.2-qtc-http/src/Wt/WLineEdit.h:115:  const WT_USTRING& text() const { return content_; }
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/http/StaticReply.C:107:      boost::starts_with(request_path, "/resources/")) {
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/http/StaticReply.C:109:    gzipReply = openStream(stream_, path_, acceptGzip);
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/http/StaticReply.C:280:    stream_.read(buf_, (std::streamsize)
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/Wt/WStringStream.C:218:  result.push_back(AsioWrapper::asio::buffer(buf_, buf_i_));
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/http/Reply.C:297:    result.insert(result.end(), contentBuffers.begin(), contentBuffers.end());
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/http/TcpConnection.C:123:  LOG_DEBUG(native() << ": startAsyncWriteResponse");
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/http/TcpConnection.C:137:  asio::async_write(*socket_, buffers,
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/http/Connection.C:512:  LOG_DEBUG(native() << ": handleWriteResponse0(): "
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/fcgi/WServer.C:193:  bool isRelayServer = args.size() < 1 || args[0] != "client";
  
#(gdb) set detach-on-fork off
#(gdb) set follow-fork-mode child
/home/sib/Projects/wt-4.11.2-qtc-http/src/fcgi/Server.C:162:  pid_t pid = fork();
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/fcgi/Server.C:155:  execv(argv[0], const_cast<char *const *>(argv));
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/fcgi/WServer.C:216:  if (configuration().webSockets()) {
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/fcgi/WServer.C:84:    if (!Server::bindUDStoStdin(conf.runDirectory() + "/server-"
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/fcgi/Server.C:58:  int s = socket(AF_UNIX, SOCK_STREAM, 0);
/home/sib/Projects/wt-4.11.2-qtc-http/src/fcgi/Server.C:312:  int s = socket(AF_UNIX, SOCK_STREAM, 0);
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/web/WebMain.C:26:{ }
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/Wt/WServer.C:101:  if (!ioService_) {
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/web/WebMain.C:51:  for (;;) {
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/web/Configuration.C:1468:  if (!runDirectory_.empty()) {
  
/home/sib/Projects/wt-4.11.2-qtc-http/src/fcgi/Server.C:404:  for (;;) {
  

