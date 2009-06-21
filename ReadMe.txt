//==========================================
// LIBCTINY - Matt Pietrek 2001
// MSDN Magazine, January 2001
//==========================================

libctiny plus some additions

obj files from:

C:\Program Files\Microsoft Visual Studio .NET 2003\Vc7\crt\src\intel\dll_lib

-----

Additional by leepa

I took this from Google's Omaha project and then made it work for my own
purposes. Figured others might find this useful so wanted to share it. 

This version is built as a Visual Studio 2008 project for your usage anywhere 
you like. There was a couple of problems with making this work but it does work 
now. 

The main issue is around intrinsic functions and castings. I have fixed up the
relevant parts and forced VC++ to use the functions provided here instead
of intrinsic ones. This loses some optimisation, yes. But overall it keeps
within the spirit of the library.

Enjoy.
