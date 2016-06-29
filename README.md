# crc16
nodejs crc16 

use

var CRC16 = require('./AppCrc');
var buffer = new Buffer('some_value');
var other = CRC16.GetCRC(buffer,buffer.length);
