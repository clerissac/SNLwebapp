SNL iCare Online Application TEST BUILD v2.2H

Root-cause repair:
- Restored the signature popup and signature canvas.
- Restored the PDF-Lib library required to create Preview and Final PDFs.
- The missing modal and missing PDF library were accidentally removed together with the old custom preview viewer.
- Signature buttons now open the signature pad.
- Preview continues to use the browser's native PDF viewer.
- Added defensive signature-canvas initialization.
- Email Collection Form and Prescription Authorization logic are unchanged.

After uploading, open:
https://clerissac.github.io/SNLwebapp/?v=22h
