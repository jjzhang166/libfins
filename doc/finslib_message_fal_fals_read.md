# Libfins API Reference

### `finslib_message_fal_fals_read( sys, faldata, fal_number );`

### Parameters

| Parameter | Type | Description |
| :--- | :--- | :--- |
|**`sys`**|`struct fins_sys_tp *`|A pointer to a structure with the FINS context|
|**`faldata`**|`char *`|Location where the FAL error information must be stored|
|**`fal_number`**|`uint16_t`|The number of the FAL number for which the message must be read|

### Return Value

| Type | Description |
| :--- | :--- |
|`int`|A return value from the list [`FINS_RETVAL_...`](fins_retval.md) indicating the result of the query|

### Description

### See Also

* [`FINS_RETVAL...`](fins_retval.md) &ndash; Libfins function return code list
* [`finslib_error_clear();`](finslib_error_clear.md)
* [`finslib_error_clear_all();`](finslib_error_clear_all.md)
* [`finslib_error_clear_current();`](finslib_error_clear_current.md)
* [`finslib_error_clear_fal();`](finslib_error_clear_fal.md)
* [`finslib_error_clear_fals();`](finslib_error_clear_fals.md)
* [`finslib_error_log_clear();`](finslib_error_log_clear.md)
* [`finslib_error_log_read();`](finslib_error_log_read.md)
* [`finslib_message_clear();`](finslib_message_clear.md)
* [`finslib_message_read();`](finslib_message_read.md)
