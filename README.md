JS-TLV
======

JavaScript TLV Decoder

HOW TO :

decoder = new TLVDecoder();

decoder.parseTLV("6F1A840E315041592E5359532E4444463031A5088801025F2D02656E");

decoder.tlv -> contains TLV structure

To compute tag's length :


decoder.encode(tag,val) -> returns TLV object


To encode DGI format :

decoder.encodeDGI(tag,val) -> returns TLV object in EMV specifiations