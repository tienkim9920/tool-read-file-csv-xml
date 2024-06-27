# tool-read-file-csv-xml
# Format File CSV
ERRCODE,ERRDESC,EN_ERRDESC,ZH_ERRDESC
1,[1]: Mã sự kiện không tồn tại,[1]: Error execute in database.,事件代码不存在
0,Giao dịch thực hiện thành công,Transaction successfull!,交易成功,

# Format File XML
<?xml version="1.0" encoding="utf-8"?>
<NewDataSet>
  <root>
    <ErrorID>0</ErrorID>
    <ErrorCode>ERR_SYSTEM_OK</ErrorCode>
    <ErrorDesc>Trade successfully!</ErrorDesc>
  </root>
</NewDataSet>

# Tải file csv hiển thị những mã ERRCODE bị trùng
# Nếu không trùng thì thêm mới vào file CSV và tải xuống
