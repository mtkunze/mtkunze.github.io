## compress PDF
gs -sDEVICE=pdfwrite -dPDFSETTINGS=/printer -dNOPAUSE -dBATCH -dUseCIEColor -sOutputFile=small.pdf viewsonic-pro8400.pdf 
# For higher compression use /ebook or /screen instead of /printer. Use /prepress for better quality.

