### Decode raw & contract data without abi

### Usages
```
// decode raw
node index.js raw=f903028203eca0a0b28ca59300440597de68db37e8cf9021fa7a5cef9ed7eee5e878241520a2aa00b9020221000574797065730100020103007a047fff057fffffff06001fffffffffffff07c2c7000008c058fffffff5433921003e303132333435363738396162636465666768696a6b6c6d6e6f707172737475767778797a4142434445464748494a4b4c4d4e4f505152535455565758595a22a00123456789abcdef0123456789abcdef0123456789abcdef0123456789abcd2302010011001030313233343536373839616263646566120004010000011300240030003100320033003400350036003700380039006100620063006400650066006700680069006a006b006c006d006e006f0070007100720073007400750076007700780079007a1400037fff000080011500037fffffff0000000080000001160003001fffffffffffff0000000000000000ffe0000000000001170003c2c700000000000042c70000180003c058fffffff5433900000000000000004058fffffff543393121000321000b613132333435363738393021001b306162636465666768696a6b6c6d6e6f707172737475767778797a210024313233343536373839306162636465666768696a6b6c6d6e6f707172737475767778797a3122000222a00123456789abcdef0123456789abcdef0123456789abcdef0123456789abcd22a0abcdef0123456789abcdef0123456789abcdef0123456789abcd012345678931230003230100230200ff230201008705a4bbf6bd54a0831e84808800000002540be40001b8c0373661313539323034346136653466353131323635626361373361363034643930623035323964316466363032626533306131396139323537363630643166353461623038393332643831643831336138633737316639333338383835643562313036366665306334373130363762353461353636346565653130623638626531663433663263366665303332643737643335353536343364363136313530613331643538393639373164366333623034353238313733323961356432353036

// decode contract data
node index.js data=21000574797065730100020103007a047fff057fffffff06001fffffffffffff07c2c7000008c058fffffff5433921003e303132333435363738396162636465666768696a6b6c6d6e6f707172737475767778797a4142434445464748494a4b4c4d4e4f505152535455565758595a22a00123456789abcdef0123456789abcdef0123456789abcdef0123456789abcd2302010011001030313233343536373839616263646566120004010000011300240030003100320033003400350036003700380039006100620063006400650066006700680069006a006b006c006d006e006f0070007100720073007400750076007700780079007a1400037fff000080011500037fffffff0000000080000001160003001fffffffffffff0000000000000000ffe0000000000001170003c2c700000000000042c70000180003c058fffffff5433900000000000000004058fffffff543393121000321000b613132333435363738393021001b306162636465666768696a6b6c6d6e6f707172737475767778797a210024313233343536373839306162636465666768696a6b6c6d6e6f707172737475767778797a3122000222a00123456789abcdef0123456789abcdef0123456789abcdef0123456789abcd22a0abcdef0123456789abcdef0123456789abcdef0123456789abcd012345678931230003230100230200ff23020100

```