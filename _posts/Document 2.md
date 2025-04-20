Lots of distributed “my stuff” ideas floating around.

Here’s an idea: let’s use relations. Let’s make relations primary.

Current “my stuff” ideas (The atmosphere/at: stuff is *super* interesting) tend to favour documents, particularly JSON documents.

Distributed “my stuff” naturally gravitates to documents for a lot of use cases, and documents are a useful way for folks to organise information.

But a document (a “drawing”, or a “word processing file”) can just be a value in a relational database, fitting in perfectly naturally. And nicely organised and flexible metadata comes for free.

But if you flip it around and make documents primary, then relations don’t really fit that well. The only thing that work is for entire relations to be a “cell value” or “field”, which is sort of fine, but you wind up with complex, extraneous addressing details (which document in which collection contains this year’s sales data?). That sort of thing should be supported, but everything is neater when relations are the basic organising principle.

Documents inside relations are perfectly natural. Relations inside documents is just a bad fit. So we should make relations primary.

Here’s another idea: since I get to store information for free on your server (I enter things on a form on your website; that data goes into a log file somewhere, if not a full blown relational table), make that useful. Give your users a limited ability to define their own relations and store their own data, on your server.

