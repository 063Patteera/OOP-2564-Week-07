# การทดลองสัปดาห์ที่ 7.1 #
เขียนโค้ด PlantUML สำหรับ type ชนิดอื่น ๆ โดยใช้วิธีเดียวกันกับขั้นตอนที่ 3 ในชนิดข้อมูล SByte เพื่อสร้าง diagram สำหรับ predefined type ทุกชนิด

## 1.sbyte ##

``` puml
@startuml
class SByte
{
  + Maxvalue : SByte
  + Minvalue : SByte

  + Parse(...) : SByte 
  + TryParse(...) : SByte
  + CompareTo(...) : SByte
  + Equals(...) : bool
  + GatHashCode() : int
  + GetTypeCode() : TypeCode
  + ToString(...) : string
}
@enduml
```

![image](https://user-images.githubusercontent.com/92082157/169660059-32cb4718-cf5d-420f-959d-85d54d3f48c2.png)
<p align = "center"> <b>รูปที่ 1</b> diagram ของ sbyte </p>

## 2.byte ##

``` puml
@startuml
class Byte
{
  + Maxvalue : byte
  + Minvalue : byte

  + Parse(...) : byte
  + TryParse(...) : byte
  + CompareTo(...) : byte
  + Equals(...) : bool
  + GatHashCode() : int
  + GetTypeCode() : TypeCode
  + ToString(...) : string
}
@enduml
```

![image](https://user-images.githubusercontent.com/92082157/169660072-2ee67975-f48f-478a-9387-6a437662e8f3.png)
<p align = "center"> <b>รูปที่ 2</b> diagram ของ byte </p>

## 3.short ##

``` puml
@startuml
class Int16
{
  + Maxvalue : short
  + Minvalue : short

  + Parse(...) : short 
  + TryParse(...) : short
  + CompareTo(...) : short
  + Equals(...) : bool
  + GatHashCode() : int
  + GetTypeCode() : TypeCode
  + ToString(...) : string
}
@enduml
```

![image](https://user-images.githubusercontent.com/92082157/169660077-b9e323ed-9306-445b-9c63-5020cb423e52.png)
<p align = "center"> <b>รูปที่ 3</b> diagram ของ short </p>

## 4.ushort ##

``` puml
@startuml
class UInt16
{
  + Maxvalue : ushort
  + Minvalue : ushort

  + Parse(...) : ushort 
  + TryParse(...) : ushort
  + CompareTo(...) : ushort
  + Equals(...) : bool
  + GatHashCode() : int
  + GetTypeCode() : TypeCode
  + ToString(...) : string
}
@enduml
```

![image](https://user-images.githubusercontent.com/92082157/169660089-f6a03da5-54dd-449b-9aa9-b96d1812c77e.png)
<p align = "center"> <b>รูปที่ 4</b> diagram ของ ushort </p>

## 5.int ##

``` puml
@startuml
class Int32
{
  + Maxvalue : int
  + Minvalue : int

  + Parse(...) : int 
  + TryParse(...) : int
  + CompareTo(...) : int
  + Equals(...) : bool
  + GatHashCode() : int
  + GetTypeCode() : TypeCode
  + ToString(...) : string
}
@enduml
```

![image](https://user-images.githubusercontent.com/92082157/169660095-5ccbee52-0b2a-40c2-ac2d-9f16d8169229.png)
<p align = "center"> <b>รูปที่ 5</b> diagram ของ int </p>

## 6.uint ##

``` puml
@startuml
class UInt32
{
  + Maxvalue : uint
  + Minvalue : uint

  + Parse(...) : uint 
  + TryParse(...) : uint
  + CompareTo(...) : uint
  + Equals(...) : bool
  + GatHashCode() : int
  + GetTypeCode() : TypeCode
  + ToString(...) : string
}
@enduml
```

![image](https://user-images.githubusercontent.com/92082157/169660108-4348d288-59b4-465c-894e-7b29ad6abe86.png)
<p align = "center"> <b>รูปที่ 6</b> diagram ของ uint </p>

## 7.long ##

``` puml
@startuml
class Int64
{
  + Maxvalue : long
  + Minvalue : long

  + Parse(...) : long 
  + TryParse(...) : long
  + CompareTo(...) : long
  + Equals(...) : bool
  + GatHashCode() : int
  + GetTypeCode() : TypeCode
  + ToString(...) : string
}
@enduml
```

![image](https://user-images.githubusercontent.com/92082157/169660115-cbc6906b-c205-470d-bc60-80ff6f0e0562.png)
<p align = "center"> <b>รูปที่ 7</b> diagram ของ long </p>

## 8.ulong ##

``` puml
@startuml
class UInt64
{
  + Maxvalue : ulong
  + Minvalue : ulong

  + Parse(...) : ulong 
  + TryParse(...) : ulong
  + CompareTo(...) : ulong
  + Equals(...) : bool
  + GatHashCode() : int
  + GetTypeCode() : TypeCode
  + ToString(...) : string
}
@enduml
```

![image](https://user-images.githubusercontent.com/92082157/169660129-6bd778a0-98c2-4235-a95a-ecad413dd701.png)
<p align = "center"> <b>รูปที่ 8</b> diagram ของ ulong </p>

## 9.float ##

``` puml
@startuml
class Single
{
  + Minvalue : float
  + Epsilon : float
  + Maxvalue : float
  + PositiveInfinity : float
  + NegativeInfinity : float
  + NaN : float

  + IsInfinity() : float
  + IsPositiveInfinity() : float
  + IsNegativeInfinity() : float
  + IsNaN() : float
  + Parse(...) : float 
  + TryParse(...) : float
  + CompareTo(...) : float
  + Equals(...) : bool
  + operator ==() : bool
  + operator !=() : bool
  + operator <() : bool
  + operator >() : bool
  + operator <=() : bool
  + operator >=() : bool
  + GatHashCode() : int
  + GetTypeCode() : TypeCode
  + ToString(...) : string
}
@enduml
```

![image](https://user-images.githubusercontent.com/92082157/169660152-864adfce-83d7-4228-94e4-3da3282ab3b4.png)
<p align = "center"> <b>รูปที่ 9</b> diagram ของ float </p>

## 10.double ##

``` puml
@startuml
class Double
{
  + Minvalue : double
  + Maxvalue : double
  + Epsilon : double
  + NegativeInfinity : double
  + PositiveInfinity : double
  + NaN : double

  + IsInfinity() : double
  + IsPositiveInfinity() : double
  + IsNegativeInfinity() : double
  + IsNaN() : double
  + Parse(...) : double
  + TryParse(...) : double
  + CompareTo(...) : double
  + Equals(...) : bool
  + operator ==() : bool
  + operator !=() : bool
  + operator <() : bool
  + operator >() : bool
  + operator <=() : bool
  + operator >=() : bool
  + GatHashCode() : int
  + GetTypeCode() : TypeCode
  + ToString(...) : string
}
@enduml
```

![image](https://user-images.githubusercontent.com/92082157/169660159-a146a4b8-573d-49c4-be5e-93307bd69292.png)
<p align = "center"> <b>รูปที่ 10</b> diagram ของ double </p>

## 11.bool ##

``` puml
@startuml
class Boolean
{
  + TrueString : string
  + FalseString : string

  + Parse(...) : bool
  + TryParse(...) : bool
  + CompareTo(...) : bool
  + Equals(...) : bool
  + GatHashCode() : int
  + GetTypeCode() : TypeCode
  + ToString(...) : string
  - TrimWhiteSpaceAndNull() : string
}
@enduml
```

![image](https://user-images.githubusercontent.com/92082157/169660171-6a4b67d5-8ba7-46ad-87e1-59aef5d1f7b7.png)
<p align = "center"> <b>รูปที่ 11</b> diagram ของ bool </p>

## 12.char ##

``` puml
@startuml
class Char
{
  + Maxvalue : char
  + Minvalue : char

  + Parse(...) : char 
  + TryParse(...) : char
  + CompareTo(...) : char
  + IsControl(...) : char
  + IsDigit(...) : char
  + IsLetter(...) : char
  + IsLetterOrDigit(...) : char
  + IsNumber(...) : char
  + IsWhiteSpace(...) : char
  + IsSeparator(...) : char
  + IsSurrogate(...) : char
  + IsHighSurrogate(...) : char
  + IsLowSurrogate(...) : char
  + IsSurrogatePair(...) : char
  + IsSymbol(...) : char
  + IsUpper(...) : char
  + IsLower(...) : char
  + IsPunctuation(...) : char
  + ToUpper(...) : char
  + ToUpperInvariant() : char
  + ToLower(...) : char
  + ToLowerInvariant() : char
  + Equals(...) : bool
  + ConvertFromUtf32() : string
  + ConvertToUtf32(...) : int
  + ToString(...) : string
  + GatHashCode() : int
  + GetNumericValue(...) : double
  + GetUnicodeCategory(...) : UnicodeCategory
  + GetTypeCode() : TypeCode
}
@enduml
```

![image](https://user-images.githubusercontent.com/92082157/169660174-9149c954-3ac2-4a5f-8654-796defb17fd3.png)
<p align = "center"> <b>รูปที่ 12</b> diagram ของ char </p>

## 13.decimal ##

``` puml
@startuml
class Decimal
{
  + Zero : decimal
  + One : decimal
  + MinusOne : decimal
  + Maxvalue : decimal
  + Minvalue : decimal

  + Parse(...) : decimal
  + TryParse(...) : decimal
  # Abs() : decimal
  + Add() : decimal
  - FCallAddSub() : decimal
  - FCallAddSubOverflowed() : decimal
  + Ceiling() : decimal
  + Compare() : decimal
  - FCallCompare() : decimal
  + CompareTo(...) : decimal
  + Divide() : decimal
  - FCallDivide() : decimal
  - FCallDivideOverflowed() : decimal
  + Floor() : decimal
  - FCallFloor() : decimal
  + GetBits() : decimal
  + Remainder() : decimal
  + Multiply() : decimal
  - FCallMultiply() : decimal
  - FCallMultiplyOverflowed() : decimal
  + Negate() : decimal
  + Round(...) : decimal
  - FCallRound() : decimal
  + Subtract() : decimal
  + Truncate() : decimal
  - FCallTruncate() : decimal
  + operator +(...) : decimal
  + operator -(...) : decimal
  + operator ++() : decimal
  + operator --() : decimal
  + operator *() : decimal
  + operator /() : decimal
  + operator %() : decimal
  + operator ==() : bool
  + operator !=() : bool
  + operator <() : bool
  + operator <=() : bool
  + operator >() : bool
  + operator >=() : bool
  + Equals(...) : bool
  + GatHashCode() : int
  + GetTypeCode() : TypeCode
  + ToString(...) : string
  + ToByte() : byte
  + ToSByte() : sbyte
  + ToInt16() : short
  + ToDouble() : double
  + ToInt32() : int
  + ToInt64() : long
  + ToUInt16() : ushort
  + ToUInt32() : uint
  + ToUInt64() : ulong
  + ToSingle() : float
  + ToOACurrency() : long
  + FromOACurrency() : decimal
}
@enduml
```

![image](https://user-images.githubusercontent.com/92082157/169660179-d72449b1-337c-4680-b6c7-2976a3e68db9.png)
<p align = "center"> <b>รูปที่ 13</b> diagram ของ decimal </p>

## 14.object ##

``` puml
@startuml
class Object
{
  + ToString() : string
  + Equals(...) : bool
  + ReferenceEquals() : bool
  + GatHashCode() : int
  + GetType() : Type
}
@enduml
```

![image](https://user-images.githubusercontent.com/92082157/169660192-22bfc7c3-6f0e-4a01-9576-7026b38f8f69.png)
<p align = "center"> <b>รูปที่ 14</b> diagram ของ object </p>

## 15.string ##

``` puml
@startuml
class String
{
  + Empty : string

  + Compare(...) : string
  + CompareTo(...) : string
  + CompareOrdinal(...) : string
  + Join(...) : string
  + Split(...) : string
  + Contains() : string
  + EndsWith(...) : string
  + IndexOf(...) : string
  + IndexOfAny(...) : string
  + LastIndexOf(...) : string
  + LastIndexOfAny(...) : string
  + PadLeft(...) : string
  + PadRight(...) : string
  + StartsWith(...) : string
  + ToLower(...) : string
  + ToLowerInvariant(...) : string
  + ToUpper(...) : string
  + ToUpperInvariant(...) : string
  + Clone() : object
  + Insert() : string
  + Replace(...) : string
  + Remove(...) : string
  + Format(...) : string
  + Copy() : string
  + Concat(...) : string
  + Intern() : string
  + IsInterned() : string
  + IsNullOrEmpty() : string
  + IsNullOrWhiteSpace() : string
  + IsNormalized(...) :  bool
  + Normalize(...) : string
  + Substring(...) : string
  + Trim(...) : string
  + TrimStart() : string
  + TrimEnd() : string
  + operator ==() : bool
  + operator !=() : bool
  + Equals(...) : bool
  + CopyTo() : void
  + GatHashCode() : int
  + GetTypeCode() : TypeCode
  + GetEnumerator() : CharEnumerator
  + ToString(...) : string
  + ToCharArray(...) : char
}
@enduml
```

![image](https://user-images.githubusercontent.com/92082157/169660205-c0b1e76a-0721-411a-a761-d932123f6a6c.png)
<p align = "center"> <b>รูปที่ 15</b> diagram ของ string </p>

# การทดลองสัปดาห์ที่ 7.2 #
แสดงรายละเอียดของ predefined type
![image](https://user-images.githubusercontent.com/92082157/169660222-4f7207cb-d6c2-45dd-81a2-e411bdf1615c.png)
<p align = "center"> <b>รูปแสดงผลที่ได้จากการรันโปรแกรม</b> </p>
