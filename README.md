# Clipboard-windows

Copying papers or text with special formats will sometimes cause line breaks, resulting in intermittent translation into Google Translate.

Therefore, this project will monitor the Windows clipboard through the win32 API so that the copied text can be replaced by spaces. newline