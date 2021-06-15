# Report from 6/15/2021, 4:41:09 PM
## Top 20 unconverted elements
- tr (177)
- td (162)
- th[scope="row"] (43)
- table.standard-table (39)
- th (17)
- dfn (16)
- span.seoSummary (14)
- kbd (13)
- table (6)
- span.blob-code-inner.blob-code-marker (5)
- table.fullwidth-table (4)
- sub (4)
- figure (3)
- p.summary (3)
- code (3)
- pre.brush:.js.highlight:.[5] (3)
- dl (2)
- th[colSpan="4"] (2)
- abbr[title="ECMAScript 5th edition"] (2)
- td[rowSpan="4"] (1)
## Details per Document
### [/en-US/docs/Web/JavaScript/Data_structures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures)
#### Invalid AST transformations
##### td (206:4) => tableCell
```
type: "paragraph"
summary: "Programming languages all have built-in data structures, but these often differ from one language to another. This article attempts to list the built-in data structures available in JavaScript and what properties they have. These can be used to build other data structures. Wherever possible, comparisons with other languages are drawn."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "If "
  type: "inlineCode"
  value: "true"
  type: "text"
  value: ", the property will be enumerated in "
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Statements/for...in"
  children:
    type: "text"
    value: "for...in"
  type: "text"
  value: " loops."
  type: "break"
  type: "text"
  value: "See also "
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Enumerability_and_ownership_of_properties"
  children:
    type: "text"
    value: "Enumerability and ownership of properties"
  type: "text"
  value: "."
```
##### tr (203:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    If <code>true</code>, the property will be enumerated in\n    <a href=\"/en-US/docs/Web/JavaScript/Reference/Statements/for...in\"\n      >for...in</a\n    >\n    loops.<br />See also\n    <a\n      href=\"/en-US/docs/Web/JavaScript/Enumerability_and_ownership_of_properties\"\n      >Enumerability and ownership of properties</a\n    >.\n  </p>\n</td>\n"
```
##### table.standard-table (180:1) => table
```
type: "html"
value: "<tr>\n  <td>[[Enumerable]]</td>\n  <td>Boolean</td>\n  <td>\n    <p>\n      If <code>true</code>, the property will be enumerated in\n      <a href=\"/en-US/docs/Web/JavaScript/Reference/Statements/for...in\"\n        >for...in</a\n      >\n      loops.<br />See also\n      <a\n        href=\"/en-US/docs/Web/JavaScript/Enumerability_and_ownership_of_properties\"\n        >Enumerability and ownership of properties</a\n      >.\n    </p>\n  </td>\n  <td><code>false</code></td>\n</tr>\n"
```
### [/en-US/docs/Web/JavaScript/Enumerability_and_ownership_of_properties](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Enumerability_and_ownership_of_properties)
#### Invalid AST transformations
##### td (35:7) => tableCell
```
type: "paragraph"
summary: "Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false."
rowIndex: 1
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/propertyIsEnumerable"
  children:
    type: "inlineCode"
    value: "propertyIsEnumerable",type: "paragraph"
summary: "Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false."
rowIndex: 1
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty"
  children:
    type: "inlineCode"
    value: "hasOwnProperty"
```
##### tr (31:5) => tableRow
```
type: "html"
value: "<th>Enumerable</th>\n",type: "html"
value: "<td>\n  <p>\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/propertyIsEnumerable\"\n        >propertyIsEnumerable</a\n      ></code\n    >\n  </p>\n  <p>\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty\"\n        >hasOwnProperty</a\n      ></code\n    >\n  </p>\n</td>\n"
```
##### td (46:7) => tableCell
```
type: "paragraph"
summary: "Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false."
rowIndex: 2
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty"
  children:
    type: "inlineCode"
    value: "hasOwnProperty"
  type: "text"
  value: " – filtered to exclude enumerables using "
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/propertyIsEnumerable"
  children:
    type: "inlineCode"
    value: "propertyIsEnumerable"
```
##### tr (42:5) => tableRow
```
type: "html"
value: "<th>Nonenumerable</th>\n",type: "html"
value: "<td>\n  <p>\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty\"\n        >hasOwnProperty</a\n      ></code\n    >\n    – filtered to exclude enumerables using\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/propertyIsEnumerable\"\n        >propertyIsEnumerable</a\n      ></code\n    >\n  </p>\n</td>\n"
```
##### td (56:7) => tableCell
```
type: "paragraph"
summary: "Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false."
rowIndex: 3
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty"
  children:
    type: "inlineCode"
    value: "hasOwnProperty"
```
##### tr (52:5) => tableRow
```
type: "html"
value: "<th>Enumerable and Nonenumerable</th>\n",type: "html"
value: "<td>\n  <p>\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty\"\n        >hasOwnProperty</a\n      ></code\n    >\n  </p>\n</td>\n"
```
##### table (21:1) => table
```
type: "html"
value: "<tr>\n  <th>Enumerable</th>\n  <td>\n    <p>\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/propertyIsEnumerable\"\n          >propertyIsEnumerable</a\n        ></code\n      >\n    </p>\n    <p>\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty\"\n          >hasOwnProperty</a\n        ></code\n      >\n    </p>\n  </td>\n  <td>Not available without extra code</td>\n  <td>Not available without extra code</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th>Nonenumerable</th>\n  <td>\n    <p>\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty\"\n          >hasOwnProperty</a\n        ></code\n      >\n      – filtered to exclude enumerables using\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/propertyIsEnumerable\"\n          >propertyIsEnumerable</a\n        ></code\n      >\n    </p>\n  </td>\n  <td>Not available without extra code</td>\n  <td>Not available without extra code</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th>Enumerable and Nonenumerable</th>\n  <td>\n    <p>\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/hasOwnProperty\"\n          >hasOwnProperty</a\n        ></code\n      >\n    </p>\n  </td>\n  <td>\n    <code\n      ><a href=\"/en-US/docs/Web/JavaScript/Reference/Operators/in\">in</a></code\n    >\n  </td>\n  <td>Not available without extra code</td>\n</tr>\n"
```
##### td (81:7) => tableCell
```
type: "paragraph"
summary: "Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false."
rowIndex: 1
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys"
  children:
    type: "inlineCode"
    value: "Object.keys",type: "paragraph"
summary: "Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false."
rowIndex: 1
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames"
  children:
    type: "inlineCode"
    value: "getOwnPropertyNames"
  type: "text"
  value: " ",type: "paragraph"
summary: "Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false."
rowIndex: 1
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols"
  children:
    type: "inlineCode"
    value: "getOwnPropertySymbols"
```
##### tr (77:5) => tableRow
```
type: "html"
value: "<th>Enumerable</th>\n",type: "html"
value: "<td>\n  <p>\n    <code\n      ><a href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys\"\n        >Object.keys</a\n      ></code\n    >\n  </p>\n  <p>\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames\"\n        >getOwnPropertyNames</a\n      ></code\n    > \n  </p>\n  <p>\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols\"\n        >getOwnPropertySymbols</a\n      ></code\n    >\n  </p>\n</td>\n"
```
##### tr (89:5) => tableRow
```
type: "html"
value: "<th>Nonenumerable</th>\n"
```
##### td (101:7) => tableCell
```
type: "paragraph"
summary: "Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false."
rowIndex: 3
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames"
  children:
    type: "inlineCode"
    value: "getOwnPropertyNames",type: "paragraph"
summary: "Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false."
rowIndex: 3
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols"
  children:
    type: "inlineCode"
    value: "getOwnPropertySymbols"
```
##### tr (97:5) => tableRow
```
type: "html"
value: "<th>Enumerable and Nonenumerable</th>\n",type: "html"
value: "<td>\n  <p>\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames\"\n        >getOwnPropertyNames</a\n      ></code\n    >\n  </p>\n  <p>\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols\"\n        >getOwnPropertySymbols</a\n      ></code\n    >\n  </p>\n</td>\n"
```
##### table (67:1) => table
```
type: "html"
value: "<tr>\n  <th>Enumerable</th>\n  <td>\n    <p>\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys\"\n          >Object.keys</a\n        ></code\n      >\n    </p>\n    <p>\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames\"\n          >getOwnPropertyNames</a\n        ></code\n      > \n    </p>\n    <p>\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols\"\n          >getOwnPropertySymbols</a\n        ></code\n      >\n    </p>\n  </td>\n  <td>Not available without extra code</td>\n  <td>Not available without extra code</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th>Nonenumerable</th>\n  <td>\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames\"\n        >getOwnPropertyNames</a\n      ></code\n    >,\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols\"\n        >getOwnPropertySymbols</a\n      ></code\n    >\n    – filtered to exclude enumerables using <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/propertyIsEnumerable\"\n        >propertyIsEnumerable</a\n      ></code\n    >\n  </td>\n  <td>Not available without extra code</td>\n  <td>Not available without extra code</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th>Enumerable and Nonenumerable</th>\n  <td>\n    <p>\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames\"\n          >getOwnPropertyNames</a\n        ></code\n      >\n    </p>\n    <p>\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols\"\n          >getOwnPropertySymbols</a\n        ></code\n      >\n    </p>\n  </td>\n  <td>Not available without extra code</td>\n  <td>Not available without extra code</td>\n</tr>\n"
```
##### td (127:7) => tableCell
```
type: "paragraph"
summary: "Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false."
rowIndex: 1
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys"
  children:
    type: "inlineCode"
    value: "Object.keys",type: "paragraph"
summary: "Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false."
rowIndex: 1
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames"
  children:
    type: "inlineCode"
    value: "getOwnPropertyNames"
  type: "text"
  value: " ",type: "paragraph"
summary: "Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false."
rowIndex: 1
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols"
  children:
    type: "inlineCode"
    value: "getOwnPropertySymbols"
```
##### td (132:7) => tableCell
```
type: "paragraph"
summary: "Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false."
rowIndex: 1
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Statements/for...in"
  children:
    type: "inlineCode"
    value: "for..in",type: "paragraph"
summary: "Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "(excluding symbols)"
```
##### tr (123:5) => tableRow
```
type: "html"
value: "<th>Enumerable</th>\n",type: "html"
value: "<td>\n  <p>\n    <code\n      ><a href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys\"\n        >Object.keys</a\n      ></code\n    >\n  </p>\n  <p>\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames\"\n        >getOwnPropertyNames</a\n      ></code\n    > \n  </p>\n  <p>\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols\"\n        >getOwnPropertySymbols</a\n      ></code\n    >\n  </p>\n</td>\n",type: "html"
value: "<td>\n  <p>\n    <code\n      ><a href=\"/en-US/docs/Web/JavaScript/Reference/Statements/for...in\"\n        >for..in</a\n      ></code\n    >\n  </p>\n  <p>(excluding symbols)</p>\n</td>\n"
```
##### tr (138:5) => tableRow
```
type: "html"
value: "<th>Nonenumerable</th>\n"
```
##### td (150:7) => tableCell
```
type: "paragraph"
summary: "Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false."
rowIndex: 3
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames"
  children:
    type: "inlineCode"
    value: "getOwnPropertyNames",type: "paragraph"
summary: "Enumerable properties are those properties whose internal enumerable flag is set to true, which is the default for properties created via simple assignment or via a property initializer. Properties defined via Object.defineProperty and such default enumerable to false."
rowIndex: 3
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols"
  children:
    type: "inlineCode"
    value: "getOwnPropertySymbols"
```
##### tr (146:5) => tableRow
```
type: "html"
value: "<th>Enumerable and Nonenumerable</th>\n",type: "html"
value: "<td>\n  <p>\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames\"\n        >getOwnPropertyNames</a\n      ></code\n    >\n  </p>\n  <p>\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols\"\n        >getOwnPropertySymbols</a\n      ></code\n    >\n  </p>\n</td>\n"
```
##### table (113:1) => table
```
type: "html"
value: "<tr>\n  <th>Enumerable</th>\n  <td>\n    <p>\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys\"\n          >Object.keys</a\n        ></code\n      >\n    </p>\n    <p>\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames\"\n          >getOwnPropertyNames</a\n        ></code\n      > \n    </p>\n    <p>\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols\"\n          >getOwnPropertySymbols</a\n        ></code\n      >\n    </p>\n  </td>\n  <td>\n    <p>\n      <code\n        ><a href=\"/en-US/docs/Web/JavaScript/Reference/Statements/for...in\"\n          >for..in</a\n        ></code\n      >\n    </p>\n    <p>(excluding symbols)</p>\n  </td>\n  <td>Not available without extra code</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th>Nonenumerable</th>\n  <td>\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames\"\n        >getOwnPropertyNames</a\n      ></code\n    >,\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols\"\n        >getOwnPropertySymbols</a\n      ></code\n    >\n    – filtered to exclude enumerables using <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/propertyIsEnumerable\"\n        >propertyIsEnumerable</a\n      ></code\n    >\n  </td>\n  <td>Not available without extra code</td>\n  <td>Not available without extra code</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th>Enumerable and Nonenumerable</th>\n  <td>\n    <p>\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyNames\"\n          >getOwnPropertyNames</a\n        ></code\n      >\n    </p>\n    <p>\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertySymbols\"\n          >getOwnPropertySymbols</a\n        ></code\n      >\n    </p>\n  </td>\n  <td>Not available without extra code</td>\n  <td>Not available without extra code</td>\n</tr>\n"
```
##### tr (247:5) => tableRow
```
type: "html"
value: "<th><code>in</code></th>\n"
```
##### tr (256:5) => tableRow
```
type: "html"
value: "<th><code>for..in</code></th>\n"
```
##### tr (265:5) => tableRow
```
type: "html"
value: "<th><code>obj.hasOwnProperty</code></th>\n"
```
##### tr (274:5) => tableRow
```
type: "html"
value: "<th><code>obj.propertyIsEnumerable</code></th>\n"
```
##### tr (283:5) => tableRow
```
type: "html"
value: "<th><code>Object.keys</code></th>\n"
```
##### tr (292:5) => tableRow
```
type: "html"
value: "<th><code>Object.getOwnPropertyNames</code></th>\n"
```
##### tr (301:5) => tableRow
```
type: "html"
value: "<th><code>Object.getOwnPropertyDescriptors</code></th>\n"
```
##### tr (310:5) => tableRow
```
type: "html"
value: "<th><code>Reflect.ownKeys()</code></th>\n"
```
##### table (234:1) => table
```
type: "html"
value: "<tr>\n  <th><code>in</code></th>\n  <td>true</td>\n  <td>true</td>\n  <td>true</td>\n  <td>true</td>\n  <td>true</td>\n  <td>true</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th><code>for..in</code></th>\n  <td>true</td>\n  <td>false</td>\n  <td>false</td>\n  <td>true</td>\n  <td>false</td>\n  <td>false</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th><code>obj.hasOwnProperty</code></th>\n  <td>true</td>\n  <td>true</td>\n  <td>true</td>\n  <td>false</td>\n  <td>false</td>\n  <td>false</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th><code>obj.propertyIsEnumerable</code></th>\n  <td>true</td>\n  <td>false</td>\n  <td>true</td>\n  <td>false</td>\n  <td>false</td>\n  <td>false</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th><code>Object.keys</code></th>\n  <td>true</td>\n  <td>false</td>\n  <td>false</td>\n  <td>false</td>\n  <td>false</td>\n  <td>false</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th><code>Object.getOwnPropertyNames</code></th>\n  <td>true</td>\n  <td>true</td>\n  <td>false</td>\n  <td>false</td>\n  <td>false</td>\n  <td>false</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th><code>Object.getOwnPropertyDescriptors</code></th>\n  <td>true</td>\n  <td>true</td>\n  <td>true</td>\n  <td>false</td>\n  <td>false</td>\n  <td>false</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th><code>Reflect.ownKeys()</code></th>\n  <td>true</td>\n  <td>true</td>\n  <td>true</td>\n  <td>false</td>\n  <td>false</td>\n  <td>false</td>\n</tr>\n"
```
### Missing conversion rules
- th (32:7)
- th (43:7)
- th (53:7)
- th (78:7)
- th (90:7)
- th (98:7)
- th (124:7)
- th (139:7)
- th (147:7)
- th (248:7)
- th (257:7)
- th (266:7)
- th (275:7)
- th (284:7)
- th (293:7)
- th (302:7)
- th (311:7)
### [/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness)
#### Invalid AST transformations
##### dl (484:1) => paragraph
```
type: "code"
lang: "js"
meta: ""
value: "let stoppingForce = obj.mass * -obj.velocity;",type: "paragraph"
summary: "There are four equality algorithms in ES2015:"
children:
  type: "text"
  value: "If "
  type: "inlineCode"
  value: "obj.velocity"
  type: "text"
  value: " is "
  type: "inlineCode"
  value: "0"
  type: "text"
  value: " (or computes to "
  type: "inlineCode"
  value: "0"
  type: "text"
  value: "), a "
  type: "inlineCode"
  value: "-0"
  type: "text"
  value: " is introduced at that place and propagates out into "
  type: "inlineCode"
  value: "stoppingForce"
  type: "text"
  value: "."
```
### [/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling)
### Missing conversion rules
- dfn (34:34)
### [/en-US/docs/Web/JavaScript/Guide/Details_of_the_Object_Model](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Details_of_the_Object_Model)
#### Invalid AST transformations
##### tr (60:3) => tableRow
```
type: "html"
value: "<th scope=\"row\">Category</th>\n"
```
##### tr (67:3) => tableRow
```
type: "html"
value: "<th scope=\"row\">Class vs. Instance</th>\n"
```
##### tr (72:3) => tableRow
```
type: "html"
value: "<th scope=\"row\">Definition</th>\n"
```
##### tr (77:3) => tableRow
```
type: "html"
value: "<th scope=\"row\">Creation of new object</th>\n"
```
##### tr (82:3) => tableRow
```
type: "html"
value: "<th scope=\"row\">Construction of object hierarchy</th>\n"
```
##### tr (87:3) => tableRow
```
type: "html"
value: "<th scope=\"row\">Inheritance model</th>\n"
```
##### tr (92:3) => tableRow
```
type: "html"
value: "<th scope=\"row\">Extension of properties</th>\n"
```
##### table.standard-table (57:1) => table
```
type: "html"
value: "<tr>\n  <th scope=\"row\">Category</th>\n  <th scope=\"col\">Class-based (Java)</th>\n  <th scope=\"col\">Prototype-based (JavaScript)</th>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Class vs. Instance</th>\n  <td>Class and instance are distinct entities.</td>\n  <td>All objects can inherit from another object.</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Definition</th>\n  <td>\n    Define a class with a class definition; instantiate a class with constructor\n    methods.\n  </td>\n  <td>Define and create a set of objects with constructor functions.</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Creation of new object</th>\n  <td>Create a single object with the <code>new</code> operator.</td>\n  <td>Same.</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Construction of object hierarchy</th>\n  <td>\n    Construct an object hierarchy by using class definitions to define\n    subclasses of existing classes.\n  </td>\n  <td>\n    Construct an object hierarchy by assigning an object as the prototype\n    associated with a constructor function.\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Inheritance model</th>\n  <td>Inherit properties by following the class chain.</td>\n  <td>Inherit properties by following the prototype chain.</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Extension of properties</th>\n  <td>\n    Class definition specifies <em>all</em> properties of all instances of a\n    class. Cannot add properties dynamically at run time.\n  </td>\n  <td>\n    Constructor function or prototype specifies an <em>initial set</em> of\n    properties. Can add or remove properties dynamically to individual objects\n    or to the entire set of objects.\n  </td>\n</tr>\n"
```
### Missing conversion rules
- th[scope="row"] (61:4)
- th[scope="row"] (68:4)
- th[scope="row"] (73:4)
- th[scope="row"] (78:4)
- th[scope="row"] (83:4)
- th[scope="row"] (88:4)
- th[scope="row"] (93:4)
- figure (310:1)
- figure (319:1)
- figure (414:1)
### [/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
#### Invalid AST transformations
##### td (280:7) => tableCell
```
type: "paragraph"
summary: "This chapter describes JavaScript's expressions and operators,\n  including assignment, comparison, arithmetic, bitwise, logical, string, ternary and\n  more."
rowIndex: 1
shouldWrap: true
children:
  type: "inlineCode"
  value: "\"3\" == var1"
```
##### tr (275:5) => tableRow
```
type: "html"
value: "<td>\n  <code>3 == var1</code>\n  <p><code>\"3\" == var1</code></p>\n  <code>3 == '3'</code>\n</td>\n"
```
##### table.standard-table (265:1) => table
```
type: "html"
value: "<tr>\n  <td>\n    <a href=\"/en-US/docs/Web/JavaScript/Reference/Operators#equality\">Equal</a>\n    (<code>==</code>)\n  </td>\n  <td>Returns <code>true</code> if the operands are equal.</td>\n  <td>\n    <code>3 == var1</code>\n    <p><code>\"3\" == var1</code></p>\n    <code>3 == '3'</code>\n  </td>\n</tr>\n"
```
### Missing conversion rules
- table.fullwidth-table (374:1)
- table.fullwidth-table (593:1)
- table.fullwidth-table (646:1)
### [/en-US/docs/Web/JavaScript/Guide/Grammar_and_types](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_types)
#### Invalid AST transformations
##### td (679:4) => tableCell
```
type: "paragraph"
summary: "This chapter discusses JavaScript's basic grammar, variable declarations, data types and literals."
rowIndex: 12
shouldWrap: true
children:
  type: "text"
  value: "The character with the Latin-1 encoding specified by the two hexadecimal digits "
  type: "emphasis"
  children:
    type: "text"
    value: "XX"
  type: "text"
  value: " between "
  type: "inlineCode"
  value: "00"
  type: "text"
  value: " and "
  type: "inlineCode"
  value: "FF"
  type: "text"
  value: "."
  type: "break"
  type: "text"
  value: "For example, "
  type: "inlineCode"
  value: "\\xA9"
  type: "text"
  value: " is the hexadecimal sequence for the copyright symbol."
```
##### tr (677:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    The character with the Latin-1 encoding specified by the two hexadecimal\n    digits <em>XX</em> between <code>00</code> and <code>FF</code>.<br />For\n    example, <code>\\xA9</code> is the hexadecimal sequence for the copyright\n    symbol.\n  </p>\n</td>\n"
```
##### table.standard-table (623:1) => table
```
type: "html"
value: "<tr>\n  <td>\n    <code>\\x<em>XX</em></code>\n  </td>\n  <td>\n    <p>\n      The character with the Latin-1 encoding specified by the two hexadecimal\n      digits <em>XX</em> between <code>00</code> and <code>FF</code>.<br />For\n      example, <code>\\xA9</code> is the hexadecimal sequence for the copyright\n      symbol.\n    </p>\n  </td>\n</tr>\n"
```
### [/en-US/docs/Web/JavaScript/Guide/Indexed_collections](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Indexed_collections)
### Missing conversion rules
- dfn (16:11)
### [/en-US/docs/Web/JavaScript/Guide/Introduction](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Introduction)
### Missing conversion rules
- kbd (115:29)
- kbd (115:45)
- kbd (115:62)
- kbd (115:99)
- kbd (115:114)
- kbd (115:132)
- kbd (148:10)
- kbd (148:25)
- kbd (148:45)
- kbd (148:61)
### [/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)
### Missing conversion rules
- p.summary (15:1)
### [/en-US/docs/Web/JavaScript/Guide/Meta_programming](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Meta_programming)
#### Invalid AST transformations
##### td (73:4) => tableCell
```
type: "list"
ordered: false
start:

spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "inlineCode"
      value: "getPrototypeOf"
      type: "text"
      value: " method must return an object or "
      type: "inlineCode"
      value: "null"
      type: "text"
      value: "."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "If "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " is not extensible, "
      type: "inlineCode"
      value: "Object.getPrototypeOf(proxy)"
      type: "text"
      value: " method must return the same value as "
      type: "inlineCode"
      value: "Object.getPrototypeOf(target)"
      type: "text"
      value: "."
```
##### tr (66:3) => tableRow
```
type: "html"
value: "<td>\n  <ul>\n    <li>\n      <code>getPrototypeOf</code> method must return an object or\n      <code>null</code>.\n    </li>\n    <li>\n      If <code><var>target</var></code> is not extensible,\n      <code>Object.getPrototypeOf(<var>proxy</var>)</code> method must return\n      the same value as <code>Object.getPrototypeOf(<var>target</var>)</code>.\n    </li>\n  </ul>\n</td>\n"
```
##### td (102:4) => tableCell
```
type: "list"
ordered: false
start:

spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "inlineCode"
      value: "getOwnPropertyDescriptor"
      type: "text"
      value: " must return an object or "
      type: "inlineCode"
      value: "undefined"
      type: "text"
      value: "."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "A property cannot be reported as non-existent if it exists as a non-configurable own property of "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: "."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "A property cannot be reported as non-existent if it exists as an own property of "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " and "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " is not extensible."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "A property cannot be reported as existent if it does not exists as an own property of "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " and "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " is not extensible."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "A property cannot be reported as non-configurable if it does not exist as an own property of "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " or if it exists as a configurable own property of "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: "."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "The result of "
      type: "inlineCode"
      value: "Object.getOwnPropertyDescriptor(target)"
      type: "text"
      value: " can be applied to "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " using "
      type: "inlineCode"
      value: "Object.defineProperty"
      type: "text"
      value: " and will not throw an exception."
```
##### tr (98:3) => tableRow
```
type: "html"
value: "<td>\n  <ul>\n    <li>\n      <code>getOwnPropertyDescriptor</code> must return an object or\n      <code>undefined</code>.\n    </li>\n    <li>\n      A property cannot be reported as non-existent if it exists as a\n      non-configurable own property of <code><var>target</var></code\n      >.\n    </li>\n    <li>\n      A property cannot be reported as non-existent if it exists as an own\n      property of <code><var>target</var></code> and\n      <code><var>target</var></code> is not extensible.\n    </li>\n    <li>\n      A property cannot be reported as existent if it does not exists as an own\n      property of <code><var>target</var></code> and\n      <code><var>target</var></code> is not extensible.\n    </li>\n    <li>\n      A property cannot be reported as non-configurable if it does not exist as\n      an own property of <code><var>target</var></code> or if it exists as a\n      configurable own property of <code><var>target</var></code\n      >.\n    </li>\n    <li>\n      The result of\n      <code>Object.getOwnPropertyDescriptor(<var>target</var>)</code> can be\n      applied to <code><var>target</var></code> using\n      <code>Object.defineProperty</code> and will not throw an exception.\n    </li>\n  </ul>\n</td>\n"
```
##### td (117:4) => tableCell
```
type: "list"
ordered: false
start:

spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "A property cannot be added if "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " is not extensible."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "A property cannot be added as (or modified to be) non-configurable if it does not exist as a non-configurable own property of "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: "."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "A property may not be non-configurable if a corresponding configurable property of "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " exists."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "If a property has a corresponding target object property, then "
      type: "inlineCode"
      value: "Object.defineProperty(target, prop, descriptor)"
      type: "text"
      value: " will not throw an exception."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "In strict mode, a "
      type: "inlineCode"
      value: "false"
      type: "text"
      value: " value returned from the "
      type: "inlineCode"
      value: "defineProperty"
      type: "text"
      value: " handler will throw a {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}} exception."
```
##### tr (113:3) => tableRow
```
type: "html"
value: "<td>\n  <ul>\n    <li>\n      A property cannot be added if <code><var>target</var></code\n      > is not extensible.\n    </li>\n    <li>\n      A property cannot be added as (or modified to be) non-configurable if it\n      does not exist as a non-configurable own property of\n      <code><var>target</var></code\n      >.\n    </li>\n    <li>\n      A property may not be non-configurable if a corresponding configurable\n      property of <code><var>target</var></code> exists.\n    </li>\n    <li>\n      If a property has a corresponding target object property, then\n      <code\n        >Object.defineProperty(<var>target</var>, <var>prop</var>,\n        <var>descriptor</var>)</code\n      >\n      will not throw an exception.\n    </li>\n    <li>\n      In strict mode, a <code>false</code> value returned from the\n      <code>defineProperty</code> handler will throw a\n      {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}} exception.\n    </li>\n  </ul>\n</td>\n"
```
##### td (129:4) => tableCell
```
type: "list"
spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "Property query"
    type: "list"
    spread: false
    children:
      type: "listItem"
      spread: false
      children:
        type: "paragraph"
        children:
          type: "text"
          value: ": "
          type: "inlineCode"
          value: "foo in proxy"
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "Inherited property query"
    type: "list"
    spread: false
    children:
      type: "listItem"
      spread: false
      children:
        type: "paragraph"
        children:
          type: "text"
          value: ": "
          type: "inlineCode"
          value: "foo in Object.create(proxy)"
          type: "break"
          type: "text"
          value: "{{anN4cmVmKCJSZWZsZWN0LmhhcygpIik=}}"
```
##### td (138:4) => tableCell
```
type: "list"
ordered: false
start:

spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "A property cannot be reported as non-existent, if it exists as a non-configurable own property of "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: "."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "A property cannot be reported as non-existent if it exists as an own property of "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " and "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " is not extensible."
```
##### tr (127:3) => tableRow
```
type: "html"
value: "<td>\n  <dl>\n    <dt>Property query</dt>\n    <dd><code>foo in proxy</code></dd>\n    <dt>Inherited property query</dt>\n    <dd>\n      <code>foo in Object.create(<var>proxy</var>)</code\n      ><br />{{anN4cmVmKCJSZWZsZWN0LmhhcygpIik=}}\n    </dd>\n  </dl>\n</td>\n",type: "html"
value: "<td>\n  <ul>\n    <li>\n      A property cannot be reported as non-existent, if it exists as a\n      non-configurable own property of <code><var>target</var></code\n      >.\n    </li>\n    <li>\n      A property cannot be reported as non-existent if it exists as an own\n      property of <code><var>target</var></code> and\n      <code><var>target</var></code> is not extensible.\n    </li>\n  </ul>\n</td>\n"
```
##### td (147:4) => tableCell
```
type: "list"
spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "Property access"
    type: "list"
    spread: false
    children:
      type: "listItem"
      spread: false
      children:
        type: "paragraph"
        children:
          type: "text"
          value: ": "
          type: "inlineCode"
          value: "proxy[foo]"
          type: "break"
          type: "inlineCode"
          value: "proxy.bar"
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "Inherited property access"
    type: "list"
    spread: false
    children:
      type: "listItem"
      spread: false
      children:
        type: "paragraph"
        children:
          type: "text"
          value: ": "
          type: "inlineCode"
          value: "Object.create(proxy)[foo]"
          type: "break"
          type: "text"
          value: "{{anN4cmVmKCJSZWZsZWN0LmdldCgpIik=}}"
```
##### td (157:4) => tableCell
```
type: "list"
ordered: false
start:

spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "The value reported for a property must be the same as the value of the corresponding "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " property if "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: "'s property is a non-writable, non-configurable data property."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "The value reported for a property must be "
      type: "inlineCode"
      value: "undefined"
      type: "text"
      value: " if the corresponding "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " property is non-configurable accessor property that has undefined as its "
      type: "inlineCode"
      value: "[[Get]]"
      type: "text"
      value: " attribute."
```
##### tr (145:3) => tableRow
```
type: "html"
value: "<td>\n  <dl>\n    <dt>Property access</dt>\n    <dd>\n      <code><var>proxy</var>[foo]</code><br /><code><var>proxy</var>.bar</code>\n    </dd>\n    <dt>Inherited property access</dt>\n    <dd>\n      <code>Object.create(<var>proxy</var>)[foo]</code\n      ><br />{{anN4cmVmKCJSZWZsZWN0LmdldCgpIik=}}\n    </dd>\n  </dl>\n</td>\n",type: "html"
value: "<td>\n  <ul>\n    <li>\n      The value reported for a property must be the same as the value of the\n      corresponding <code><var>target</var></code> property if\n      <code><var>target</var></code\n      >'s property is a non-writable, non-configurable data property.\n    </li>\n    <li>\n      The value reported for a property must be <code>undefined</code> if the\n      corresponding <code><var>target</var></code> property is non-configurable\n      accessor property that has undefined as its\n      <code>[[Get]]</code> attribute.\n    </li>\n  </ul>\n</td>\n"
```
##### td (166:4) => tableCell
```
type: "list"
spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "Property assignment"
    type: "list"
    spread: false
    children:
      type: "listItem"
      spread: false
      children:
        type: "paragraph"
        children:
          type: "text"
          value: ": "
          type: "inlineCode"
          value: "proxy[foo] = bar"
          type: "break"
          type: "inlineCode"
          value: "proxy.foo = bar"
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "Inherited property assignment"
    type: "list"
    spread: false
    children:
      type: "listItem"
      spread: false
      children:
        type: "paragraph"
        children:
          type: "text"
          value: ": "
          type: "inlineCode"
          value: "Object.create(proxy)[foo] = bar"
          type: "break"
          type: "text"
          value: "{{anN4cmVmKCJSZWZsZWN0LnNldCgpIik=}}"
```
##### td (176:4) => tableCell
```
type: "list"
ordered: false
start:

spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "Cannot change the value of a property to be different from the value of the corresponding "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " property if the corresponding "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " property is a non-writable, non-configurable data property."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "Cannot set the value of a property if the corresponding "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " property is a non-configurable accessor property that has "
      type: "inlineCode"
      value: "undefined"
      type: "text"
      value: " as its "
      type: "inlineCode"
      value: "[[Set]]"
      type: "text"
      value: " attribute."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "In strict mode, a "
      type: "inlineCode"
      value: "false"
      type: "text"
      value: " return value from the "
      type: "inlineCode"
      value: "set"
      type: "text"
      value: " handler will throw a {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}} exception."
```
##### tr (164:3) => tableRow
```
type: "html"
value: "<td>\n  <dl>\n    <dt>Property assignment</dt>\n    <dd>\n      <code><var>proxy</var>[foo] = bar</code><br /><code\n        ><var>proxy</var>.foo = bar</code\n      >\n    </dd>\n    <dt>Inherited property assignment</dt>\n    <dd>\n      <code>Object.create(<var>proxy</var>)[foo] = bar</code\n      ><br />{{anN4cmVmKCJSZWZsZWN0LnNldCgpIik=}}\n    </dd>\n  </dl>\n</td>\n",type: "html"
value: "<td>\n  <ul>\n    <li>\n      Cannot change the value of a property to be different from the value of\n      the corresponding <code><var>target</var></code> property if the\n      corresponding <code><var>target</var></code> property is a non-writable,\n      non-configurable data property.\n    </li>\n    <li>\n      Cannot set the value of a property if the corresponding\n      <code><var>target</var></code> property is a non-configurable accessor\n      property that has <code>undefined</code> as its\n      <code>[[Set]]</code> attribute.\n    </li>\n    <li>\n      In strict mode, a <code>false</code> return value from the\n      <code>set</code> handler will throw a {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}}\n      exception.\n    </li>\n  </ul>\n</td>\n"
```
##### td (186:4) => tableCell
```
type: "list"
spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "Property deletion"
    type: "list"
    spread: false
    children:
      type: "listItem"
      spread: false
      children:
        type: "paragraph"
        children:
          type: "text"
          value: ": "
          type: "inlineCode"
          value: "delete proxy[foo]"
          type: "break"
          type: "inlineCode"
          value: "delete proxy.foo"
          type: "break"
          type: "text"
          value: "{{anN4cmVmKCJSZWZsZWN0LmRlbGV0ZVByb3BlcnR5KCkiKQ==}}"
```
##### tr (184:3) => tableRow
```
type: "html"
value: "<td>\n  <dl>\n    <dt>Property deletion</dt>\n    <dd>\n      <code>delete <var>proxy</var>[foo]</code><br /><code\n        >delete <var>proxy</var>.foo</code\n      ><br />{{anN4cmVmKCJSZWZsZWN0LmRlbGV0ZVByb3BlcnR5KCkiKQ==}}\n    </dd>\n  </dl>\n</td>\n"
```
##### td (198:4) => tableCell
```
type: "list"
spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "Property enumeration / "
      type: "inlineCode"
      value: "for...in"
      type: "text"
      value: ":"
    type: "list"
    spread: false
    children:
      type: "listItem"
      spread: false
      children:
        type: "paragraph"
        children:
          type: "text"
          value: ": "
          type: "inlineCode"
          value: "for (let name in proxy) {...}"
          type: "break"
          type: "text"
          value: "{{anN4cmVmKCJSZWZsZWN0LmVudW1lcmF0ZSgpIik=}}"
```
##### tr (196:3) => tableRow
```
type: "html"
value: "<td>\n  <dl>\n    <dt>Property enumeration / <code>for...in</code>:</dt>\n    <dd>\n      <code>for (let name in <var>proxy</var>) {...}</code\n      ><br />{{anN4cmVmKCJSZWZsZWN0LmVudW1lcmF0ZSgpIik=}}\n    </dd>\n  </dl>\n</td>\n"
```
##### td (213:4) => tableCell
```
type: "list"
ordered: false
start:

spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "The result of "
      type: "inlineCode"
      value: "ownKeys"
      type: "text"
      value: " is a List."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "The Type of each result List element is either {{anN4cmVmKCJTdHJpbmciKQ==}} or {{anN4cmVmKCJTeW1ib2wiKQ==}}."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "The result List must contain the keys of all non-configurable own properties of "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: "."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "If the "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " object is not extensible, then the result List must contain all the keys of the own properties of "
      type: "inlineCode"
      value: "target"
      type: "text"
      value: " and no other values."
```
##### tr (207:3) => tableRow
```
type: "html"
value: "<td>\n  <ul>\n    <li>The result of <code>ownKeys</code> is a List.</li>\n    <li>\n      The Type of each result List element is either\n      {{anN4cmVmKCJTdHJpbmciKQ==}} or {{anN4cmVmKCJTeW1ib2wiKQ==}}.\n    </li>\n    <li>\n      The result List must contain the keys of all non-configurable own\n      properties of <code><var>target</var></code\n      >.\n    </li>\n    <li>\n      If the <code><var>target</var></code> object is not extensible, then the\n      result List must contain all the keys of the own properties of\n      <code><var>target</var></code\n      > and no other values.\n    </li>\n  </ul>\n</td>\n"
```
##### table.standard-table (57:1) => table
```
type: "html"
value: "<tr>\n  <td>\n    {{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9Qcm94eS9nZXRQcm90b3R5cGVPZiIsICJoYW5kbGVyLmdldFByb3RvdHlwZU9mKCkiKQ==}}\n  </td>\n  <td>\n    {{anN4cmVmKCJPYmplY3QuZ2V0UHJvdG90eXBlT2YoKSIp}}<br />{{anN4cmVmKCJSZWZsZWN0LmdldFByb3RvdHlwZU9mKCkiKQ==}}<br />{{anN4cmVmKCJPYmplY3QvcHJvdG8iLCAiX19wcm90b19fIik=}}<br />{{anN4cmVmKCJPYmplY3QucHJvdG90eXBlLmlzUHJvdG90eXBlT2YoKSIp}}<br />{{anN4cmVmKCJPcGVyYXRvcnMvaW5zdGFuY2VvZiIsICJpbnN0YW5jZW9mIik=}}\n  </td>\n  <td>\n    <ul>\n      <li>\n        <code>getPrototypeOf</code> method must return an object or\n        <code>null</code>.\n      </li>\n      <li>\n        If <code><var>target</var></code> is not extensible,\n        <code>Object.getPrototypeOf(<var>proxy</var>)</code> method must return\n        the same value as <code>Object.getPrototypeOf(<var>target</var>)</code>.\n      </li>\n    </ul>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    {{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9Qcm94eS9nZXRPd25Qcm9wZXJ0eURlc2NyaXB0b3IiLCAiaGFuZGxlci5nZXRPd25Qcm9wZXJ0eURlc2NyaXB0b3IoKSIp}}\n  </td>\n  <td>\n    {{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlEZXNjcmlwdG9yKCkiKQ==}}<br />{{anN4cmVmKCJSZWZsZWN0LmdldE93blByb3BlcnR5RGVzY3JpcHRvcigpIik=}}\n  </td>\n  <td>\n    <ul>\n      <li>\n        <code>getOwnPropertyDescriptor</code> must return an object or\n        <code>undefined</code>.\n      </li>\n      <li>\n        A property cannot be reported as non-existent if it exists as a\n        non-configurable own property of <code><var>target</var></code\n        >.\n      </li>\n      <li>\n        A property cannot be reported as non-existent if it exists as an own\n        property of <code><var>target</var></code> and\n        <code><var>target</var></code> is not extensible.\n      </li>\n      <li>\n        A property cannot be reported as existent if it does not exists as an\n        own property of <code><var>target</var></code> and\n        <code><var>target</var></code> is not extensible.\n      </li>\n      <li>\n        A property cannot be reported as non-configurable if it does not\n        exist as an own property of <code><var>target</var></code> or if it\n        exists as a configurable own property of <code><var>target</var></code\n        >.\n      </li>\n      <li>\n        The result of\n        <code>Object.getOwnPropertyDescriptor(<var>target</var>)</code> can be\n        applied to <code><var>target</var></code> using\n        <code>Object.defineProperty</code> and will not throw an exception.\n      </li>\n    </ul>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    {{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9Qcm94eS9kZWZpbmVQcm9wZXJ0eSIsICJoYW5kbGVyLmRlZmluZVByb3BlcnR5KCkiKQ==}}\n  </td>\n  <td>\n    {{anN4cmVmKCJPYmplY3QuZGVmaW5lUHJvcGVydHkoKSIp}}<br />{{anN4cmVmKCJSZWZsZWN0LmRlZmluZVByb3BlcnR5KCkiKQ==}}\n  </td>\n  <td>\n    <ul>\n      <li>\n        A property cannot be added if <code><var>target</var></code\n        > is not extensible.\n      </li>\n      <li>\n        A property cannot be added as (or modified to be) non-configurable if it\n        does not exist as a non-configurable own property of\n        <code><var>target</var></code\n        >.\n      </li>\n      <li>\n        A property may not be non-configurable if a corresponding configurable\n        property of <code><var>target</var></code> exists.\n      </li>\n      <li>\n        If a property has a corresponding target object property, then\n        <code\n          >Object.defineProperty(<var>target</var>, <var>prop</var>,\n          <var>descriptor</var>)</code\n        >\n        will not throw an exception.\n      </li>\n      <li>\n        In strict mode, a <code>false</code> value returned from the\n        <code>defineProperty</code> handler will throw a\n        {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}} exception.\n      </li>\n    </ul>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    {{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9Qcm94eS9oYXMiLCAiaGFuZGxlci5oYXMoKSIp}}\n  </td>\n  <td>\n    <dl>\n      <dt>Property query</dt>\n      <dd><code>foo in proxy</code></dd>\n      <dt>Inherited property query</dt>\n      <dd>\n        <code>foo in Object.create(<var>proxy</var>)</code\n        ><br />{{anN4cmVmKCJSZWZsZWN0LmhhcygpIik=}}\n      </dd>\n    </dl>\n  </td>\n  <td>\n    <ul>\n      <li>\n        A property cannot be reported as non-existent, if it exists as a\n        non-configurable own property of <code><var>target</var></code\n        >.\n      </li>\n      <li>\n        A property cannot be reported as non-existent if it exists as an own\n        property of <code><var>target</var></code> and\n        <code><var>target</var></code> is not extensible.\n      </li>\n    </ul>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    {{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9Qcm94eS9nZXQiLCAiaGFuZGxlci5nZXQoKSIp}}\n  </td>\n  <td>\n    <dl>\n      <dt>Property access</dt>\n      <dd>\n        <code><var>proxy</var>[foo]</code><br /><code\n          ><var>proxy</var>.bar</code\n        >\n      </dd>\n      <dt>Inherited property access</dt>\n      <dd>\n        <code>Object.create(<var>proxy</var>)[foo]</code\n        ><br />{{anN4cmVmKCJSZWZsZWN0LmdldCgpIik=}}\n      </dd>\n    </dl>\n  </td>\n  <td>\n    <ul>\n      <li>\n        The value reported for a property must be the same as the value of the\n        corresponding <code><var>target</var></code> property if\n        <code><var>target</var></code\n        >'s property is a non-writable, non-configurable data property.\n      </li>\n      <li>\n        The value reported for a property must be <code>undefined</code> if the\n        corresponding <code><var>target</var></code> property is\n        non-configurable accessor property that has undefined as its\n        <code>[[Get]]</code> attribute.\n      </li>\n    </ul>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    {{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9Qcm94eS9zZXQiLCAiaGFuZGxlci5zZXQoKSIp}}\n  </td>\n  <td>\n    <dl>\n      <dt>Property assignment</dt>\n      <dd>\n        <code><var>proxy</var>[foo] = bar</code><br /><code\n          ><var>proxy</var>.foo = bar</code\n        >\n      </dd>\n      <dt>Inherited property assignment</dt>\n      <dd>\n        <code>Object.create(<var>proxy</var>)[foo] = bar</code\n        ><br />{{anN4cmVmKCJSZWZsZWN0LnNldCgpIik=}}\n      </dd>\n    </dl>\n  </td>\n  <td>\n    <ul>\n      <li>\n        Cannot change the value of a property to be different from the value of\n        the corresponding <code><var>target</var></code> property if the\n        corresponding <code><var>target</var></code> property is a non-writable,\n        non-configurable data property.\n      </li>\n      <li>\n        Cannot set the value of a property if the corresponding\n        <code><var>target</var></code> property is a non-configurable accessor\n        property that has <code>undefined</code> as its\n        <code>[[Set]]</code> attribute.\n      </li>\n      <li>\n        In strict mode, a <code>false</code> return value from the\n        <code>set</code> handler will throw a {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}}\n        exception.\n      </li>\n    </ul>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    {{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9Qcm94eS9kZWxldGVQcm9wZXJ0eSIsICJoYW5kbGVyLmRlbGV0ZVByb3BlcnR5KCkiKQ==}}\n  </td>\n  <td>\n    <dl>\n      <dt>Property deletion</dt>\n      <dd>\n        <code>delete <var>proxy</var>[foo]</code><br /><code\n          >delete <var>proxy</var>.foo</code\n        ><br />{{anN4cmVmKCJSZWZsZWN0LmRlbGV0ZVByb3BlcnR5KCkiKQ==}}\n      </dd>\n    </dl>\n  </td>\n  <td>\n    A property cannot be deleted if it exists as a non-configurable own property\n    of <code><var>target</var></code\n    >.\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    {{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9oYW5kbGVyL2VudW1lcmF0ZSIsICJoYW5kbGVyLmVudW1lcmF0ZSgpIik=}}\n  </td>\n  <td>\n    <dl>\n      <dt>Property enumeration / <code>for...in</code>:</dt>\n      <dd>\n        <code>for (let name in <var>proxy</var>) {...}</code\n        ><br />{{anN4cmVmKCJSZWZsZWN0LmVudW1lcmF0ZSgpIik=}}\n      </dd>\n    </dl>\n  </td>\n  <td>The <code>enumerate</code> method must return an object.</td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    {{anN4cmVmKCJHbG9iYWxfT2JqZWN0cy9Qcm94eS9Qcm94eS9vd25LZXlzIiwgImhhbmRsZXIub3duS2V5cygpIik=}}\n  </td>\n  <td>\n    {{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlOYW1lcygpIik=}}<br />{{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlTeW1ib2xzKCkiKQ==}}<br />{{anN4cmVmKCJPYmplY3Qua2V5cygpIik=}}<br />{{anN4cmVmKCJSZWZsZWN0Lm93bktleXMoKSIp}}\n  </td>\n  <td>\n    <ul>\n      <li>The result of <code>ownKeys</code> is a List.</li>\n      <li>\n        The Type of each result List element is either\n        {{anN4cmVmKCJTdHJpbmciKQ==}} or {{anN4cmVmKCJTeW1ib2wiKQ==}}.\n      </li>\n      <li>\n        The result List must contain the keys of all non-configurable own\n        properties of <code><var>target</var></code\n        >.\n      </li>\n      <li>\n        If the <code><var>target</var></code> object is not extensible, then the\n        result List must contain all the keys of the own properties of\n        <code><var>target</var></code\n        > and no other values.\n      </li>\n    </ul>\n  </td>\n</tr>\n"
```
### Missing conversion rules
- dfn (34:44)
- dfn (34:115)
- dfn (34:194)
### [/en-US/docs/Web/JavaScript/Guide/Numbers_and_dates](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Numbers_and_dates)
#### Invalid AST transformations
##### td (253:4) => tableCell
```
type: "paragraph"
summary: "This chapter introduces the concepts, objects and functions used to work with and perform calculations using numbers and dates in JavaScript. This includes using numbers written in various bases including decimal, binary, and hexadecimal, as well as the use of the global {{anN4cmVmKCJNYXRoIik=}} object to perform a wide variety of mathematical operations on numbers."
rowIndex: 6
shouldWrap: true
children:
  type: "text"
  value: "{{anN4cmVmKCJNYXRoLnBvdyIsICJwb3coKSIp}}, {{anN4cmVmKCJNYXRoLmV4cCIsICJleHAoKSIp}}, {{anN4cmVmKCJNYXRoLmV4cG0xIiwgImV4cG0xKCkiKQ==}}, {{anN4cmVmKCJNYXRoLmxvZzEwIiwgImxvZzEwKCkiKQ==}}, {{anN4cmVmKCJNYXRoLmxvZzFwIiwgImxvZzFwKCkiKQ==}}, {{anN4cmVmKCJNYXRoLmxvZzIiLCAibG9nMigpIik=}}"
```
##### tr (252:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    {{anN4cmVmKCJNYXRoLnBvdyIsICJwb3coKSIp}},\n    {{anN4cmVmKCJNYXRoLmV4cCIsICJleHAoKSIp}},\n    {{anN4cmVmKCJNYXRoLmV4cG0xIiwgImV4cG0xKCkiKQ==}},\n    {{anN4cmVmKCJNYXRoLmxvZzEwIiwgImxvZzEwKCkiKQ==}},\n    {{anN4cmVmKCJNYXRoLmxvZzFwIiwgImxvZzFwKCkiKQ==}},\n    {{anN4cmVmKCJNYXRoLmxvZzIiLCAibG9nMigpIik=}}\n  </p>\n</td>\n"
```
##### table.standard-table (223:1) => table
```
type: "html"
value: "<tr>\n  <td>\n    <p>\n      {{anN4cmVmKCJNYXRoLnBvdyIsICJwb3coKSIp}},\n      {{anN4cmVmKCJNYXRoLmV4cCIsICJleHAoKSIp}},\n      {{anN4cmVmKCJNYXRoLmV4cG0xIiwgImV4cG0xKCkiKQ==}},\n      {{anN4cmVmKCJNYXRoLmxvZzEwIiwgImxvZzEwKCkiKQ==}},\n      {{anN4cmVmKCJNYXRoLmxvZzFwIiwgImxvZzFwKCkiKQ==}},\n      {{anN4cmVmKCJNYXRoLmxvZzIiLCAibG9nMigpIik=}}\n    </p>\n  </td>\n  <td>Exponential and logarithmic functions.</td>\n</tr>\n"
```
### Missing conversion rules
- dfn (176:68)
### [/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions)
#### Invalid AST transformations
##### td (34:4) => tableCell
```
type: "paragraph"
summary: "Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions)."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "Matches the beginning of input. If the multiline flag is set to true, also matches immediately after a line break character. For example, "
  type: "inlineCode"
  value: "/^A/"
  type: "text"
  value: " does not match the \"A\" in \"an A\", but does match the first \"A\" in \"An A\".",type: "blockquote"
children:
  type: "paragraph"
  children:
    type: "strong"
    children:
      type: "text"
      value: "Note:"
    type: "text"
    value: " This character has a different meaning when it appears at the start of a "
    type: "link"
    title:

    url: "/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges"
    children:
      type: "text"
      value: "group"
    type: "text"
    value: "."
```
##### tr (32:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches the beginning of input. If the multiline flag is set to true, also\n    matches immediately after a line break character. For example,\n    <code>/^A/</code> does not match the \"A\" in \"an A\", but does match the first\n    \"A\" in \"An A\".\n  </p>\n  <div class=\"notecard note\">\n    <p>\n      <strong>Note:</strong> This character has a different meaning when it\n      appears at the start of a\n      <a\n        href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges\"\n        >group</a\n      >.\n    </p>\n  </div>\n</td>\n"
```
##### td (44:4) => tableCell
```
type: "paragraph"
summary: "Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions)."
rowIndex: 2
shouldWrap: true
children:
  type: "text"
  value: "Matches the end of input. If the multiline flag is set to true, also matches immediately before a line break character. For example, "
  type: "inlineCode"
  value: "/t$/"
  type: "text"
  value: " does not match the \"t\" in \"eater\", but does match it in \"eat\"."
```
##### tr (42:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches the end of input. If the multiline flag is set to true, also matches\n    immediately before a line break character. For example,\n    <code>/t$/</code> does not match the \"t\" in \"eater\", but does match it in\n    \"eat\".\n  </p>\n</td>\n"
```
##### td (50:4) => tableCell
```
type: "paragraph"
summary: "Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions)."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "Matches a word boundary. This is the position where a word character is not followed or preceded by another word-character, such as between a letter and a space. Note that a matched word boundary is not included in the match. In other words, the length of a matched word boundary is zero.",type: "paragraph"
summary: "Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions)."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "Examples:",type: "list"
ordered: false
start:

spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "inlineCode"
      value: "/\\bm/"
      type: "text"
      value: " matches the \"m\" in \"moon\"."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "inlineCode"
      value: "/oo\\b/"
      type: "text"
      value: " does not match the \"oo\" in \"moon\", because \"oo\" is followed by \"n\" which is a word character."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "inlineCode"
      value: "/oon\\b/"
      type: "text"
      value: " matches the \"oon\" in \"moon\", because \"oon\" is the end of the string, thus not followed by a word character."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "inlineCode"
      value: "/\\w\\b\\w/"
      type: "text"
      value: " will never match anything, because a word character can never be followed by both a non-word and a word character.",type: "paragraph"
summary: "Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions)."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "To match a backspace character ("
  type: "inlineCode"
  value: "[\\b]"
  type: "text"
  value: "), see "
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes"
  children:
    type: "text"
    value: "Character Classes"
  type: "text"
  value: "."
```
##### tr (48:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches a word boundary. This is the position where a word character is not\n    followed or preceded by another word-character, such as between a letter and\n    a space. Note that a matched word boundary is not included in the match. In\n    other words, the length of a matched word boundary is zero.\n  </p>\n  <p>Examples:</p>\n  <ul>\n    <li><code>/\\bm/</code> matches the \"m\" in \"moon\".</li>\n    <li>\n      <code>/oo\\b/</code> does not match the \"oo\" in \"moon\", because \"oo\" is\n      followed by \"n\" which is a word character.\n    </li>\n    <li>\n      <code>/oon\\b/</code> matches the \"oon\" in \"moon\", because \"oon\" is the end\n      of the string, thus not followed by a word character.\n    </li>\n    <li>\n      <code>/\\w\\b\\w/</code> will never match anything, because a word character\n      can never be followed by both a non-word and a word character.\n    </li>\n  </ul>\n  <p>\n    To match a backspace character (<code>[\\b]</code>), see\n    <a\n      href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes\"\n      >Character Classes</a\n    >.\n  </p>\n</td>\n"
```
##### td (67:4) => tableCell
```
type: "paragraph"
summary: "Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions)."
rowIndex: 4
shouldWrap: true
children:
  type: "text"
  value: "Matches a non-word boundary. This is a position where the previous and next character are of the same type: Either both must be words, or both must be non-words, for example between two letters or between two spaces. The beginning and end of a string are considered non-words. Same as the matched word boundary, the matched non-word boundary is also not included in the match. For example, "
  type: "inlineCode"
  value: "/\\Bon/"
  type: "text"
  value: " matches \"on\" in \"at noon\", and "
  type: "inlineCode"
  value: "/ye\\B/"
  type: "text"
  value: " matches \"ye\" in \"possibly yesterday\"."
```
##### tr (65:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches a non-word boundary. This is a position where the previous and next\n    character are of the same type: Either both must be words, or both must be\n    non-words, for example between two letters or between two spaces. The\n    beginning and end of a string are considered non-words. Same as the matched\n    word boundary, the matched non-word boundary is also not included in the\n    match. For example, <code>/\\Bon/</code> matches \"on\" in \"at noon\", and\n    <code>/ye\\B/</code> matches \"ye\" in \"possibly yesterday\".\n  </p>\n</td>\n"
```
##### table.standard-table (24:1) => table
```
type: "html"
value: "<tr>\n  <td><code>^</code></td>\n  <td>\n    <p>\n      Matches the beginning of input. If the multiline flag is set to true, also\n      matches immediately after a line break character. For example,\n      <code>/^A/</code> does not match the \"A\" in \"an A\", but does match the\n      first \"A\" in \"An A\".\n    </p>\n    <div class=\"notecard note\">\n      <p>\n        <strong>Note:</strong> This character has a different meaning when it\n        appears at the start of a\n        <a\n          href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges\"\n          >group</a\n        >.\n      </p>\n    </div>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>$</code></td>\n  <td>\n    <p>\n      Matches the end of input. If the multiline flag is set to true, also\n      matches immediately before a line break character. For example,\n      <code>/t$/</code> does not match the \"t\" in \"eater\", but does match it in\n      \"eat\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\b</code></td>\n  <td>\n    <p>\n      Matches a word boundary. This is the position where a word character is\n      not followed or preceded by another word-character, such as between a\n      letter and a space. Note that a matched word boundary is not included in\n      the match. In other words, the length of a matched word boundary is zero.\n    </p>\n    <p>Examples:</p>\n    <ul>\n      <li><code>/\\bm/</code> matches the \"m\" in \"moon\".</li>\n      <li>\n        <code>/oo\\b/</code> does not match the \"oo\" in \"moon\", because \"oo\" is\n        followed by \"n\" which is a word character.\n      </li>\n      <li>\n        <code>/oon\\b/</code> matches the \"oon\" in \"moon\", because \"oon\" is the\n        end of the string, thus not followed by a word character.\n      </li>\n      <li>\n        <code>/\\w\\b\\w/</code> will never match anything, because a word\n        character can never be followed by both a non-word and a word character.\n      </li>\n    </ul>\n    <p>\n      To match a backspace character (<code>[\\b]</code>), see\n      <a\n        href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes\"\n        >Character Classes</a\n      >.\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\B</code></td>\n  <td>\n    <p>\n      Matches a non-word boundary. This is a position where the previous and\n      next character are of the same type: Either both must be words, or both\n      must be non-words, for example between two letters or between two\n      spaces. The beginning and end of a string are considered non-words. Same\n      as the matched word boundary, the matched non-word boundary is also not\n      included in the match. For example, <code>/\\Bon/</code> matches \"on\" in\n      \"at noon\", and <code>/ye\\B/</code> matches \"ye\" in \"possibly yesterday\".\n    </p>\n  </td>\n</tr>\n"
```
##### td (90:4) => tableCell
```
type: "paragraph"
summary: "Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions)."
rowIndex: 1
shouldWrap: true
children:
  type: "strong"
  children:
    type: "text"
    value: "Lookahead assertion:"
  type: "text"
  value: " "
  type: "text"
  value: "Matches \"x\" only if \"x\" is followed by \"y\". For example, /"
  type: "inlineCode"
  value: "Jack(?=Sprat)/"
  type: "text"
  value: " matches \"Jack\" only if it is followed by \"Sprat\"."
  type: "break"
  type: "inlineCode"
  value: "/Jack(?=Sprat|Frost)/"
  type: "text"
  value: " matches \"Jack\" only if it is followed by \"Sprat\" or \"Frost\". However, neither \"Sprat\" nor \"Frost\" is part of the match results."
```
##### tr (88:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <strong>Lookahead assertion: </strong>Matches \"x\" only if \"x\" is followed by\n    \"y\". For example, /<code>Jack(?=Sprat)/</code> matches \"Jack\" only if it is\n    followed by \"Sprat\".<br /><code>/Jack(?=Sprat|Frost)/</code> matches \"Jack\"\n    only if it is followed by \"Sprat\" or \"Frost\". However, neither \"Sprat\" nor\n    \"Frost\" is part of the match results.\n  </p>\n</td>\n"
```
##### td (97:4) => tableCell
```
type: "paragraph"
summary: "Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions)."
rowIndex: 2
shouldWrap: true
children:
  type: "strong"
  children:
    type: "text"
    value: "Negative lookahead assertion:"
  type: "text"
  value: " "
  type: "text"
  value: "Matches \"x\" only if \"x\" is not followed by \"y\". For example, "
  type: "inlineCode"
  value: "/\\d+(?!\\.)/"
  type: "text"
  value: " matches a number only if it is not followed by a decimal point. "
  type: "inlineCode"
  value: "/\\d+(?!\\.)/.exec('3.141')"
  type: "text"
  value: " matches \"141\" but not \"3\"."
```
##### tr (95:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <strong>Negative lookahead assertion: </strong>Matches \"x\" only if \"x\" is\n    not followed by \"y\". For example, <code>/\\d+(?!\\.)/</code> matches a number\n    only if it is not followed by a decimal point. <code\n      >/\\d+(?!\\.)/.exec('3.141')</code\n    >\n    matches \"141\" but not \"3\".\n  </p>\n</td>\n"
```
##### td (103:4) => tableCell
```
type: "paragraph"
summary: "Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions)."
rowIndex: 3
shouldWrap: true
children:
  type: "strong"
  children:
    type: "text"
    value: "Lookbehind assertion:"
  type: "text"
  value: " "
  type: "text"
  value: "Matches \"x\" only if \"x\" is preceded by \"y\". For example, "
  type: "inlineCode"
  value: "/(?<=Jack)Sprat/"
  type: "text"
  value: " matches \"Sprat\" only if it is preceded by \"Jack\". "
  type: "inlineCode"
  value: "/(?<=Jack|Tom)Sprat/"
  type: "text"
  value: " matches \"Sprat\" only if it is preceded by \"Jack\" or \"Tom\". However, neither \"Jack\" nor \"Tom\" is part of the match results."
```
##### tr (101:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <strong>Lookbehind assertion: </strong>Matches \"x\" only if \"x\" is\n    preceded by \"y\". For example, <code>/(?&#x3C;=Jack)Sprat/</code> matches\n    \"Sprat\" only if it is preceded by \"Jack\". <code\n      >/(?&#x3C;=Jack|Tom)Sprat/</code\n    >\n    matches \"Sprat\" only if it is preceded by \"Jack\" or \"Tom\". However, neither\n    \"Jack\" nor \"Tom\" is part of the match results.\n  </p>\n</td>\n"
```
##### td (109:4) => tableCell
```
type: "paragraph"
summary: "Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions)."
rowIndex: 4
shouldWrap: true
children:
  type: "strong"
  children:
    type: "text"
    value: "Negative lookbehind assertion:"
  type: "text"
  value: " "
  type: "text"
  value: "Matches \"x\" only if \"x\" is not preceded by \"y\". For example, "
  type: "inlineCode"
  value: "/(?<!-)\\d+/"
  type: "text"
  value: " matches a number only if it is not preceded by a minus sign. "
  type: "inlineCode"
  value: "/(?<!-)\\d+/.exec('3')"
  type: "text"
  value: " matches \"3\". "
  type: "inlineCode"
  value: "/(?<!-)\\d+/.exec('-3')"
  type: "text"
  value: "  match is not found because the number is preceded by the minus sign."
```
##### tr (107:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <strong>Negative lookbehind assertion: </strong>Matches \"x\" only if \"x\" is\n    not preceded by \"y\". For example, <code>/(?&#x3C;!-)\\d+/</code> matches a\n    number only if it is not preceded by a minus sign. <code\n      >/(?&#x3C;!-)\\d+/.exec('3')</code\n    >\n    matches \"3\". <code>/(?&#x3C;!-)\\d+/.exec('-3')</code>  match is not found\n    because the number is preceded by the minus sign.\n  </p>\n</td>\n"
```
##### table.standard-table (80:1) => table
```
type: "html"
value: "<tr>\n  <td><code>x(?=y)</code></td>\n  <td>\n    <p>\n      <strong>Lookahead assertion: </strong>Matches \"x\" only if \"x\" is followed\n      by \"y\". For example, /<code>Jack(?=Sprat)/</code> matches \"Jack\" only if\n      it is followed by \"Sprat\".<br /><code>/Jack(?=Sprat|Frost)/</code> matches\n      \"Jack\" only if it is followed by \"Sprat\" or \"Frost\". However, neither\n      \"Sprat\" nor \"Frost\" is part of the match results.\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>x(?!y)</code></td>\n  <td>\n    <p>\n      <strong>Negative lookahead assertion: </strong>Matches \"x\" only if \"x\" is\n      not followed by \"y\". For example, <code>/\\d+(?!\\.)/</code> matches a\n      number only if it is not followed by a decimal point. <code\n        >/\\d+(?!\\.)/.exec('3.141')</code\n      >\n      matches \"141\" but not \"3\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>(?&#x3C;=y)x</code></td>\n  <td>\n    <p>\n      <strong>Lookbehind assertion: </strong>Matches \"x\" only if \"x\" is\n      preceded by \"y\". For example, <code>/(?&#x3C;=Jack)Sprat/</code> matches\n      \"Sprat\" only if it is preceded by \"Jack\". <code\n        >/(?&#x3C;=Jack|Tom)Sprat/</code\n      >\n      matches \"Sprat\" only if it is preceded by \"Jack\" or \"Tom\". However,\n      neither \"Jack\" nor \"Tom\" is part of the match results.\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>(?&#x3C;!y)x</code></td>\n  <td>\n    <p>\n      <strong>Negative lookbehind assertion: </strong>Matches \"x\" only if \"x\" is\n      not preceded by \"y\". For example, <code>/(?&#x3C;!-)\\d+/</code> matches a\n      number only if it is not preceded by a minus sign. <code\n        >/(?&#x3C;!-)\\d+/.exec('3')</code\n      >\n      matches \"3\". <code>/(?&#x3C;!-)\\d+/.exec('-3')</code>  match is not found\n      because the number is preceded by the minus sign.\n    </p>\n  </td>\n</tr>\n"
```
### [/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes)
#### Invalid AST transformations
##### td (34:4) => tableCell
```
type: "paragraph"
summary: "Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "Has one of the following meanings:",type: "list"
ordered: false
start:

spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "Matches any single character "
      type: "emphasis"
      children:
        type: "text"
        value: "except"
      type: "text"
      value: " line terminators: "
      type: "inlineCode"
      value: "\\n"
      type: "text"
      value: ", "
      type: "inlineCode"
      value: "\\r"
      type: "text"
      value: ", "
      type: "inlineCode"
      value: "\\u2028"
      type: "text"
      value: " or "
      type: "inlineCode"
      value: "\\u2029"
      type: "text"
      value: ". For example, "
      type: "inlineCode"
      value: "/.y/"
      type: "text"
      value: " matches \"my\" and \"ay\", but not \"yes\", in \"yes make my day\"."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "Inside a character class, the dot loses its special meaning and matches a literal dot.",type: "paragraph"
summary: "Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "Note that the "
  type: "inlineCode"
  value: "m"
  type: "text"
  value: " multiline flag doesn't change the dot behavior. So to match a pattern across multiple lines, the character class "
  type: "inlineCode"
  value: "[^]"
  type: "text"
  value: " can be used — it will match any character including newlines.",type: "paragraph"
summary: "Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "ES2018 added the "
  type: "inlineCode"
  value: "s"
  type: "text"
  value: " \"dotAll\" flag, which allows the dot to also match line terminators."
```
##### tr (32:3) => tableRow
```
type: "html"
value: "<td>\n  <p>Has one of the following meanings:</p>\n  <ul>\n    <li>\n      Matches any single character <em>except</em> line terminators:\n      <code>\\n</code>, <code>\\r</code>, <code>\\u2028</code> or\n      <code>\\u2029</code>. For example, <code>/.y/</code> matches \"my\" and \"ay\",\n      but not \"yes\", in \"yes make my day\".\n    </li>\n    <li>\n      Inside a character class, the dot loses its special meaning and matches a\n      literal dot.\n    </li>\n  </ul>\n  <p>\n    Note that the <code>m</code> multiline flag doesn't change the dot behavior.\n    So to match a pattern across multiple lines, the character class\n    <code>[^]</code> can be used — it will match any character including\n    newlines.\n  </p>\n  <p>\n    ES2018 added the <code>s</code> \"dotAll\" flag, which allows the dot to also\n    match line terminators.\n  </p>\n</td>\n"
```
##### td (49:4) => tableCell
```
type: "paragraph"
summary: "Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits."
rowIndex: 2
shouldWrap: true
children:
  type: "text"
  value: "Matches any digit (Arabic numeral). Equivalent to "
  type: "inlineCode"
  value: "[0-9]"
  type: "text"
  value: ". For example, "
  type: "inlineCode"
  value: "/\\d/"
  type: "text"
  value: " or "
  type: "inlineCode"
  value: "/[0-9]/"
  type: "text"
  value: " matches \"2\" in \"B2 is the suite number\"."
```
##### tr (47:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches any digit (Arabic numeral). Equivalent to <code>[0-9]</code>. For\n    example, <code>/\\d/</code> or <code>/[0-9]/</code> matches \"2\" in \"B2 is the\n    suite number\".\n  </p>\n</td>\n"
```
##### td (55:4) => tableCell
```
type: "paragraph"
summary: "Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "Matches any character that is not a digit (Arabic numeral). Equivalent to "
  type: "inlineCode"
  value: "[^0-9]"
  type: "text"
  value: ". For example, "
  type: "inlineCode"
  value: "/\\D/"
  type: "text"
  value: " or "
  type: "inlineCode"
  value: "/[^0-9]/"
  type: "text"
  value: " matches \"B\" in \"B2 is the suite number\"."
```
##### tr (53:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches any character that is not a digit (Arabic numeral). Equivalent to\n    <code>[^0-9]</code>. For example, <code>/\\D/</code> or\n    <code>/[^0-9]/</code> matches \"B\" in \"B2 is the suite number\".\n  </p>\n</td>\n"
```
##### td (61:4) => tableCell
```
type: "paragraph"
summary: "Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits."
rowIndex: 4
shouldWrap: true
children:
  type: "text"
  value: "Matches any alphanumeric character from the basic Latin alphabet, including the underscore. Equivalent to "
  type: "inlineCode"
  value: "[A-Za-z0-9_]"
  type: "text"
  value: ". For example, "
  type: "inlineCode"
  value: "/\\w/"
  type: "text"
  value: " matches \"a\" in \"apple\", \"5\" in \"$5.28\", \"3\" in \"3D\" and \"m\" in \"Émanuel\"."
```
##### tr (59:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches any alphanumeric character from the basic Latin alphabet, including\n    the underscore. Equivalent to <code>[A-Za-z0-9_]</code>. For example,\n    <code>/\\w/</code> matches \"a\" in \"apple\", \"5\" in \"$5.28\", \"3\" in \"3D\" and\n    \"m\" in \"Émanuel\".\n  </p>\n</td>\n"
```
##### td (67:4) => tableCell
```
type: "paragraph"
summary: "Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits."
rowIndex: 5
shouldWrap: true
children:
  type: "text"
  value: "Matches any character that is not a word character from the basic Latin alphabet. Equivalent to "
  type: "inlineCode"
  value: "[^A-Za-z0-9_]"
  type: "text"
  value: ". For example, "
  type: "inlineCode"
  value: "/\\W/"
  type: "text"
  value: " or "
  type: "inlineCode"
  value: "/[^A-Za-z0-9_]/"
  type: "text"
  value: " matches \"%\" in \"50%\" and \"É\" in \"Émanuel\"."
```
##### tr (65:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches any character that is not a word character from the basic Latin\n    alphabet. Equivalent to <code>[^A-Za-z0-9_]</code>. For example,\n    <code>/\\W/</code> or <code>/[^A-Za-z0-9_]/</code> matches \"%\" in \"50%\" and\n    \"É\" in \"Émanuel\".\n  </p>\n</td>\n"
```
##### td (73:4) => tableCell
```
type: "paragraph"
summary: "Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits."
rowIndex: 6
shouldWrap: true
children:
  type: "text"
  value: "Matches a single white space character, including space, tab, form feed, line feed, and other Unicode spaces. Equivalent to "
  type: "inlineCode"
  value: "[ \\f\\n\\r\\t\\v\\u00a0\\u1680\\u2000-\\u200a\\u2028\\u2029\\u202f\\u205f\\u3000\\ufeff]"
  type: "text"
  value: ". For example, "
  type: "inlineCode"
  value: "/\\s\\w*/"
  type: "text"
  value: " matches \" bar\" in \"foo bar\"."
```
##### tr (71:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches a single white space character, including space, tab, form feed,\n    line feed, and other Unicode spaces. Equivalent to\n    <code\n      >[\n      \\f\\n\\r\\t\\v\\u00a0\\u1680\\u2000-\\u200a\\u2028\\u2029\\u202f\\u205f\\u3000\\ufeff]</code\n    >. For example, <code>/\\s\\w*/</code> matches \" bar\" in \"foo bar\".\n  </p>\n</td>\n"
```
##### td (79:4) => tableCell
```
type: "paragraph"
summary: "Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits."
rowIndex: 7
shouldWrap: true
children:
  type: "text"
  value: "Matches a single character other than white space. Equivalent to "
  type: "inlineCode"
  value: "[^ \\f\\n\\r\\t\\v\\u00a0\\u1680\\u2000-\\u200a\\u2028\\u2029\\u202f\\u205f\\u3000\\ufeff]"
  type: "text"
  value: ". For example, "
  type: "inlineCode"
  value: "/\\S\\w*/"
  type: "text"
  value: " matches \"foo\" in \"foo bar\"."
```
##### tr (77:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches a single character other than white space. Equivalent to\n    <code\n      >[^\n      \\f\\n\\r\\t\\v\\u00a0\\u1680\\u2000-\\u200a\\u2028\\u2029\\u202f\\u205f\\u3000\\ufeff]</code\n    >. For example, <code>/\\S\\w*/</code> matches \"foo\" in \"foo bar\".\n  </p>\n</td>\n"
```
##### td (113:4) => tableCell
```
type: "paragraph"
summary: "Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits."
rowIndex: 15
shouldWrap: true
children:
  type: "text"
  value: "Matches a control character using "
  type: "link"
  title:

  url: "https://en.wikipedia.org/wiki/Caret_notation"
  children:
    type: "text"
    value: "caret notation"
  type: "text"
  value: ", where \"X\" is a letter from A–Z (corresponding to codepoints "
  type: "inlineCode"
  value: "U+0001"
  type: "emphasis"
  children:
    type: "text"
    value: "–"
  type: "inlineCode"
  value: "U+001F"
  type: "text"
  value: "). For example, "
  type: "inlineCode"
  value: "/\\cM/"
  type: "text"
  value: " matches \"\\r\" in \"\\r\\n\"."
```
##### tr (111:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches a control character using\n    <a href=\"https://en.wikipedia.org/wiki/Caret_notation\">caret notation</a>,\n    where \"X\" is a letter from A–Z (corresponding to codepoints\n    <code>U+0001</code><em>–</em><code>U+001F</code>). For example,\n    <code>/\\cM/</code> matches \"\\r\" in \"\\r\\n\".\n  </p>\n</td>\n"
```
##### td (135:4) => tableCell
```
type: "paragraph"
summary: "Character classes distinguish kinds of characters such as, for example, distinguishing between letters and digits."
rowIndex: 20
shouldWrap: true
children:
  type: "text"
  value: "Indicates that the following character should be treated specially, or \"escaped\". It behaves one of two ways.",type: "list"
ordered: false
start:

spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "For characters that are usually treated literally, indicates that the next character is special and not to be interpreted literally. For example, "
      type: "inlineCode"
      value: "/b/"
      type: "text"
      value: " matches the character \"b\". By placing a backslash in front of \"b\", that is by using "
      type: "inlineCode"
      value: "/\\b/"
      type: "text"
      value: ", the character becomes special to mean match a word boundary."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "For characters that are usually treated specially, indicates that the next character is not special and should be interpreted literally. For example, \"*\" is a special character that means 0 or more occurrences of the preceding character should be matched; for example, "
      type: "inlineCode"
      value: "/a*/"
      type: "text"
      value: " means match 0 or more \"a\"s. To match "
      type: "inlineCode"
      value: "*"
      type: "text"
      value: " literally, precede it with a backslash; for example, "
      type: "inlineCode"
      value: "/a\\*/"
      type: "text"
      value: " matches \"a*\".",type: "blockquote"
children:
  type: "paragraph"
  children:
    type: "strong"
    children:
      type: "text"
      value: "Note:"
    type: "text"
    value: " To match this character literally, escape it with itself. In other words to search for "
    type: "inlineCode"
    value: "\\"
    type: "text"
    value: " use "
    type: "inlineCode"
    value: "/\\\\/"
    type: "text"
    value: "."
```
##### tr (133:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Indicates that the following character should be treated specially, or\n    \"escaped\". It behaves one of two ways.\n  </p>\n  <ul>\n    <li>\n      For characters that are usually treated literally, indicates that the next\n      character is special and not to be interpreted literally. For example,\n      <code>/b/</code> matches the character \"b\". By placing a backslash in\n      front of \"b\", that is by using <code>/\\b/</code>, the character becomes\n      special to mean match a word boundary.\n    </li>\n    <li>\n      For characters that are usually treated specially, indicates that the next\n      character is not special and should be interpreted literally. For example,\n      \"*\" is a special character that means 0 or more occurrences of the\n      preceding character should be matched; for example,\n      <code>/a*/</code> means match 0 or more \"a\"s. To match\n      <code>*</code> literally, precede it with a backslash; for example,\n      <code>/a\\*/</code> matches \"a*\".\n    </li>\n  </ul>\n  <div class=\"notecard note\">\n    <p>\n      <strong>Note:</strong> To match this character literally, escape it with\n      itself. In other words to search for <code>\\</code> use <code>/\\\\/</code>.\n    </p>\n  </div>\n</td>\n"
```
##### table.standard-table (22:1) => table
```
type: "html"
value: "<tr>\n  <td><code>.</code></td>\n  <td>\n    <p>Has one of the following meanings:</p>\n    <ul>\n      <li>\n        Matches any single character <em>except</em> line terminators:\n        <code>\\n</code>, <code>\\r</code>, <code>\\u2028</code> or\n        <code>\\u2029</code>. For example, <code>/.y/</code> matches \"my\" and\n        \"ay\", but not \"yes\", in \"yes make my day\".\n      </li>\n      <li>\n        Inside a character class, the dot loses its special meaning and matches\n        a literal dot.\n      </li>\n    </ul>\n    <p>\n      Note that the <code>m</code> multiline flag doesn't change the dot\n      behavior. So to match a pattern across multiple lines, the character class\n      <code>[^]</code> can be used — it will match any character including\n      newlines.\n    </p>\n    <p>\n      ES2018 added the <code>s</code> \"dotAll\" flag, which allows the dot to\n      also match line terminators.\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\d</code></td>\n  <td>\n    <p>\n      Matches any digit (Arabic numeral). Equivalent to <code>[0-9]</code>. For\n      example, <code>/\\d/</code> or <code>/[0-9]/</code> matches \"2\" in \"B2 is\n      the suite number\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\D</code></td>\n  <td>\n    <p>\n      Matches any character that is not a digit (Arabic numeral). Equivalent to\n      <code>[^0-9]</code>. For example, <code>/\\D/</code> or\n      <code>/[^0-9]/</code> matches \"B\" in \"B2 is the suite number\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\w</code></td>\n  <td>\n    <p>\n      Matches any alphanumeric character from the basic Latin alphabet,\n      including the underscore. Equivalent to <code>[A-Za-z0-9_]</code>. For\n      example, <code>/\\w/</code> matches \"a\" in \"apple\", \"5\" in \"$5.28\", \"3\" in\n      \"3D\" and \"m\" in \"Émanuel\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\W</code></td>\n  <td>\n    <p>\n      Matches any character that is not a word character from the basic Latin\n      alphabet. Equivalent to <code>[^A-Za-z0-9_]</code>. For example,\n      <code>/\\W/</code> or <code>/[^A-Za-z0-9_]/</code> matches \"%\" in \"50%\" and\n      \"É\" in \"Émanuel\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\s</code></td>\n  <td>\n    <p>\n      Matches a single white space character, including space, tab, form feed,\n      line feed, and other Unicode spaces. Equivalent to\n      <code\n        >[\n        \\f\\n\\r\\t\\v\\u00a0\\u1680\\u2000-\\u200a\\u2028\\u2029\\u202f\\u205f\\u3000\\ufeff]</code\n      >. For example, <code>/\\s\\w*/</code> matches \" bar\" in \"foo bar\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\S</code></td>\n  <td>\n    <p>\n      Matches a single character other than white space. Equivalent to\n      <code\n        >[^\n        \\f\\n\\r\\t\\v\\u00a0\\u1680\\u2000-\\u200a\\u2028\\u2029\\u202f\\u205f\\u3000\\ufeff]</code\n      >. For example, <code>/\\S\\w*/</code> matches \"foo\" in \"foo bar\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code>\\c<em>X</em></code>\n  </td>\n  <td>\n    <p>\n      Matches a control character using\n      <a href=\"https://en.wikipedia.org/wiki/Caret_notation\">caret notation</a>,\n      where \"X\" is a letter from A–Z (corresponding to codepoints\n      <code>U+0001</code><em>–</em><code>U+001F</code>). For example,\n      <code>/\\cM/</code> matches \"\\r\" in \"\\r\\n\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\</code></td>\n  <td>\n    <p>\n      Indicates that the following character should be treated specially, or\n      \"escaped\". It behaves one of two ways.\n    </p>\n    <ul>\n      <li>\n        For characters that are usually treated literally, indicates that the\n        next character is special and not to be interpreted literally. For\n        example, <code>/b/</code> matches the character \"b\". By placing a\n        backslash in front of \"b\", that is by using <code>/\\b/</code>, the\n        character becomes special to mean match a word boundary.\n      </li>\n      <li>\n        For characters that are usually treated specially, indicates that the\n        next character is not special and should be interpreted literally. For\n        example, \"*\" is a special character that means 0 or more occurrences of\n        the preceding character should be matched; for example,\n        <code>/a*/</code> means match 0 or more \"a\"s. To match\n        <code>*</code> literally, precede it with a backslash; for example,\n        <code>/a\\*/</code> matches \"a*\".\n      </li>\n    </ul>\n    <div class=\"notecard note\">\n      <p>\n        <strong>Note:</strong> To match this character literally, escape it with\n        itself. In other words to search for <code>\\</code> use\n        <code>/\\\\/</code>.\n      </p>\n    </div>\n  </td>\n</tr>\n"
```
### [/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Cheatsheet](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Cheatsheet)
#### Invalid AST transformations
##### td (30:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "Has one of the following meanings:",type: "list"
ordered: false
start:

spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "Matches any single character "
      type: "emphasis"
      children:
        type: "text"
        value: "except"
      type: "text"
      value: " line terminators: "
      type: "inlineCode"
      value: "\\n"
      type: "text"
      value: ", "
      type: "inlineCode"
      value: "\\r"
      type: "text"
      value: ", "
      type: "inlineCode"
      value: "\\u2028"
      type: "text"
      value: " or "
      type: "inlineCode"
      value: "\\u2029"
      type: "text"
      value: ". For example, "
      type: "inlineCode"
      value: "/.y/"
      type: "text"
      value: " matches \"my\" and \"ay\", but not \"yes\", in \"yes make my day\"."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "Inside a character class, the dot loses its special meaning and matches a literal dot.",type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "Note that the "
  type: "inlineCode"
  value: "m"
  type: "text"
  value: " multiline flag doesn't change the dot behavior. So to match a pattern across multiple lines, the character class "
  type: "inlineCode"
  value: "[^]"
  type: "text"
  value: " can be used — it will match any character including newlines.",type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "ES2018 added the "
  type: "inlineCode"
  value: "s"
  type: "text"
  value: " \"dotAll\" flag, which allows the dot to also match line terminators."
```
##### tr (28:3) => tableRow
```
type: "html"
value: "<td>\n  <p>Has one of the following meanings:</p>\n  <ul>\n    <li>\n      Matches any single character <em>except</em> line terminators:\n      <code>\\n</code>, <code>\\r</code>, <code>\\u2028</code> or\n      <code>\\u2029</code>. For example, <code>/.y/</code> matches \"my\" and \"ay\",\n      but not \"yes\", in \"yes make my day\".\n    </li>\n    <li>\n      Inside a character class, the dot loses its special meaning and matches a\n      literal dot.\n    </li>\n  </ul>\n  <p>\n    Note that the <code>m</code> multiline flag doesn't change the dot behavior.\n    So to match a pattern across multiple lines, the character class\n    <code>[^]</code> can be used — it will match any character including\n    newlines.\n  </p>\n  <p>\n    ES2018 added the <code>s</code> \"dotAll\" flag, which allows the dot to also\n    match line terminators.\n  </p>\n</td>\n"
```
##### td (45:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 2
shouldWrap: true
children:
  type: "text"
  value: "Matches any digit (Arabic numeral). Equivalent to "
  type: "inlineCode"
  value: "[0-9]"
  type: "text"
  value: ". For example, "
  type: "inlineCode"
  value: "/\\d/"
  type: "text"
  value: " or "
  type: "inlineCode"
  value: "/[0-9]/"
  type: "text"
  value: " matches \"2\" in \"B2 is the suite number\"."
```
##### tr (43:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches any digit (Arabic numeral). Equivalent to <code>[0-9]</code>. For\n    example, <code>/\\d/</code> or <code>/[0-9]/</code> matches \"2\" in \"B2 is the\n    suite number\".\n  </p>\n</td>\n"
```
##### td (51:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "Matches any character that is not a digit (Arabic numeral). Equivalent to "
  type: "inlineCode"
  value: "[^0-9]"
  type: "text"
  value: ". For example, "
  type: "inlineCode"
  value: "/\\D/"
  type: "text"
  value: " or "
  type: "inlineCode"
  value: "/[^0-9]/"
  type: "text"
  value: " matches \"B\" in \"B2 is the suite number\"."
```
##### tr (49:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches any character that is not a digit (Arabic numeral). Equivalent to\n    <code>[^0-9]</code>. For example, <code>/\\D/</code> or\n    <code>/[^0-9]/</code> matches \"B\" in \"B2 is the suite number\".\n  </p>\n</td>\n"
```
##### td (57:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 4
shouldWrap: true
children:
  type: "text"
  value: "Matches any alphanumeric character from the basic Latin alphabet, including the underscore. Equivalent to "
  type: "inlineCode"
  value: "[A-Za-z0-9_]"
  type: "text"
  value: ". For example, "
  type: "inlineCode"
  value: "/\\w/"
  type: "text"
  value: " matches \"a\" in \"apple\", \"5\" in \"$5.28\", and \"3\" in \"3D\"."
```
##### tr (55:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches any alphanumeric character from the basic Latin alphabet, including\n    the underscore. Equivalent to <code>[A-Za-z0-9_]</code>. For example,\n    <code>/\\w/</code> matches \"a\" in \"apple\", \"5\" in \"$5.28\", and \"3\" in \"3D\".\n  </p>\n</td>\n"
```
##### td (63:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 5
shouldWrap: true
children:
  type: "text"
  value: "Matches any character that is not a word character from the basic Latin alphabet. Equivalent to "
  type: "inlineCode"
  value: "[^A-Za-z0-9_]"
  type: "text"
  value: ". For example, "
  type: "inlineCode"
  value: "/\\W/"
  type: "text"
  value: " or "
  type: "inlineCode"
  value: "/[^A-Za-z0-9_]/"
  type: "text"
  value: " matches \"%\" in \"50%\"."
```
##### tr (61:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches any character that is not a word character from the basic Latin\n    alphabet. Equivalent to <code>[^A-Za-z0-9_]</code>. For example,\n    <code>/\\W/</code> or <code>/[^A-Za-z0-9_]/</code> matches \"%\" in \"50%\".\n  </p>\n</td>\n"
```
##### td (69:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 6
shouldWrap: true
children:
  type: "text"
  value: "Matches a single white space character, including space, tab, form feed, line feed, and other Unicode spaces. Equivalent to "
  type: "inlineCode"
  value: "[ \\f\\n\\r\\t\\v\\u00a0\\u1680\\u2000-\\u200a\\u2028\\u2029\\u202f\\u205f\\u3000\\ufeff]"
  type: "text"
  value: ". For example, "
  type: "inlineCode"
  value: "/\\s\\w*/"
  type: "text"
  value: " matches \" bar\" in \"foo bar\"."
```
##### tr (67:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches a single white space character, including space, tab, form feed,\n    line feed, and other Unicode spaces. Equivalent to\n    <code\n      >[\n      \\f\\n\\r\\t\\v\\u00a0\\u1680\\u2000-\\u200a\\u2028\\u2029\\u202f\\u205f\\u3000\\ufeff]</code\n    >. For example, <code>/\\s\\w*/</code> matches \" bar\" in \"foo bar\".\n  </p>\n</td>\n"
```
##### td (75:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 7
shouldWrap: true
children:
  type: "text"
  value: "Matches a single character other than white space. Equivalent to "
  type: "inlineCode"
  value: "[^ \\f\\n\\r\\t\\v\\u00a0\\u1680\\u2000-\\u200a\\u2028\\u2029\\u202f\\u205f\\u3000\\ufeff]"
  type: "text"
  value: ". For example, "
  type: "inlineCode"
  value: "/\\S\\w*/"
  type: "text"
  value: " matches \"foo\" in \"foo bar\"."
```
##### tr (73:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches a single character other than white space. Equivalent to\n    <code\n      >[^\n      \\f\\n\\r\\t\\v\\u00a0\\u1680\\u2000-\\u200a\\u2028\\u2029\\u202f\\u205f\\u3000\\ufeff]</code\n    >. For example, <code>/\\S\\w*/</code> matches \"foo\" in \"foo bar\".\n  </p>\n</td>\n"
```
##### td (109:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 15
shouldWrap: true
children:
  type: "text"
  value: "Matches a control character using "
  type: "link"
  title:

  url: "https://en.wikipedia.org/wiki/Caret_notation"
  children:
    type: "text"
    value: "caret notation"
  type: "text"
  value: ", where \"X\" is a letter from A–Z (corresponding to codepoints "
  type: "inlineCode"
  value: "U+0001"
  type: "emphasis"
  children:
    type: "text"
    value: "–"
  type: "inlineCode"
  value: "U+001F"
  type: "text"
  value: "). For example, "
  type: "inlineCode"
  value: "/\\cM/"
  type: "text"
  value: " matches \"\\r\" in \"\\r\\n\"."
```
##### tr (107:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches a control character using\n    <a href=\"https://en.wikipedia.org/wiki/Caret_notation\">caret notation</a>,\n    where \"X\" is a letter from A–Z (corresponding to codepoints\n    <code>U+0001</code><em>–</em><code>U+001F</code>). For example,\n    <code>/\\cM/</code> matches \"\\r\" in \"\\r\\n\".\n  </p>\n</td>\n"
```
##### td (127:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 19
shouldWrap: true
children:
  type: "text"
  value: "Indicates that the following character should be treated specially, or \"escaped\". It behaves one of two ways.",type: "list"
ordered: false
start:

spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "For characters that are usually treated literally, indicates that the next character is special and not to be interpreted literally. For example, "
      type: "inlineCode"
      value: "/b/"
      type: "text"
      value: " matches the character \"b\". By placing a backslash in front of \"b\", that is by using "
      type: "inlineCode"
      value: "/\\b/"
      type: "text"
      value: ", the character becomes special to mean match a word boundary."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "For characters that are usually treated specially, indicates that the next character is not special and should be interpreted literally. For example, \"*\" is a special character that means 0 or more occurrences of the preceding character should be matched; for example, "
      type: "inlineCode"
      value: "/a*/"
      type: "text"
      value: " means match 0 or more \"a\"s. To match "
      type: "inlineCode"
      value: "*"
      type: "text"
      value: " literally, precede it with a backslash; for example, "
      type: "inlineCode"
      value: "/a\\*/"
      type: "text"
      value: " matches \"a*\".",type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 19
shouldWrap: true
children:
  type: "text"
  value: "Note that some characters like "
  type: "inlineCode"
  value: ":"
  type: "text"
  value: ", "
  type: "inlineCode"
  value: "-"
  type: "text"
  value: ", "
  type: "inlineCode"
  value: "@"
  type: "text"
  value: ", etc. neither have a special meaning when escaped nor when unescaped. Escape sequences like "
  type: "inlineCode"
  value: "\\:"
  type: "text"
  value: ", "
  type: "inlineCode"
  value: "\\-"
  type: "text"
  value: ", "
  type: "inlineCode"
  value: "\\@"
  type: "text"
  value: " will be equivalent to their literal, unescaped character equivalents in regular expressions. However, in regular expressions with the "
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Guide/Regular_Expressions#advanced_searching_with_flags_2"
  children:
    type: "text"
    value: "unicode flag"
  type: "text"
  value: ", these will cause an "
  type: "emphasis"
  children:
    type: "text"
    value: "invalid identity escape"
  type: "text"
  value: " error. This is done to ensure backward compatibility with existing code that uses new escape sequences like "
  type: "inlineCode"
  value: "\\p"
  type: "text"
  value: " or "
  type: "inlineCode"
  value: "\\k"
  type: "text"
  value: ".",type: "blockquote"
children:
  type: "paragraph"
  children:
    type: "strong"
    children:
      type: "text"
      value: "Note:"
    type: "text"
    value: " To match this character literally, escape it with itself. In other words to search for "
    type: "inlineCode"
    value: "\\"
    type: "text"
    value: " use "
    type: "inlineCode"
    value: "/\\\\/"
    type: "text"
    value: "."
```
##### tr (125:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Indicates that the following character should be treated specially, or\n    \"escaped\". It behaves one of two ways.\n  </p>\n  <ul>\n    <li>\n      For characters that are usually treated literally, indicates that the next\n      character is special and not to be interpreted literally. For example,\n      <code>/b/</code> matches the character \"b\". By placing a backslash in\n      front of \"b\", that is by using <code>/\\b/</code>, the character becomes\n      special to mean match a word boundary.\n    </li>\n    <li>\n      For characters that are usually treated specially, indicates that the next\n      character is not special and should be interpreted literally. For example,\n      \"*\" is a special character that means 0 or more occurrences of the\n      preceding character should be matched; for example,\n      <code>/a*/</code> means match 0 or more \"a\"s. To match\n      <code>*</code> literally, precede it with a backslash; for example,\n      <code>/a\\*/</code> matches \"a*\".\n    </li>\n  </ul>\n  <p>\n    Note that some characters like <code>:</code>, <code>-</code>,\n    <code>@</code>, etc. neither have a special meaning when escaped nor when\n    unescaped. Escape sequences like <code>\\:</code>, <code>\\-</code>,\n    <code>\\@</code> will be equivalent to their literal, unescaped character\n    equivalents in regular expressions. However, in regular expressions with the\n    <a\n      href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions#advanced_searching_with_flags_2\"\n      >unicode flag</a\n    >, these will cause an <em>invalid identity escape</em> error. This is done\n    to ensure backward compatibility with existing code that uses new escape\n    sequences like <code>\\p</code> or <code>\\k</code>.\n  </p>\n  <div class=\"notecard note\">\n    <p>\n      <strong>Note:</strong> To match this character literally, escape it with\n      itself. In other words to search for <code>\\</code> use <code>/\\\\/</code>.\n    </p>\n  </div>\n</td>\n"
```
##### table.standard-table (18:1) => table
```
type: "html"
value: "<tr>\n  <td><code>.</code></td>\n  <td>\n    <p>Has one of the following meanings:</p>\n    <ul>\n      <li>\n        Matches any single character <em>except</em> line terminators:\n        <code>\\n</code>, <code>\\r</code>, <code>\\u2028</code> or\n        <code>\\u2029</code>. For example, <code>/.y/</code> matches \"my\" and\n        \"ay\", but not \"yes\", in \"yes make my day\".\n      </li>\n      <li>\n        Inside a character class, the dot loses its special meaning and matches\n        a literal dot.\n      </li>\n    </ul>\n    <p>\n      Note that the <code>m</code> multiline flag doesn't change the dot\n      behavior. So to match a pattern across multiple lines, the character class\n      <code>[^]</code> can be used — it will match any character including\n      newlines.\n    </p>\n    <p>\n      ES2018 added the <code>s</code> \"dotAll\" flag, which allows the dot to\n      also match line terminators.\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\d</code></td>\n  <td>\n    <p>\n      Matches any digit (Arabic numeral). Equivalent to <code>[0-9]</code>. For\n      example, <code>/\\d/</code> or <code>/[0-9]/</code> matches \"2\" in \"B2 is\n      the suite number\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\D</code></td>\n  <td>\n    <p>\n      Matches any character that is not a digit (Arabic numeral). Equivalent to\n      <code>[^0-9]</code>. For example, <code>/\\D/</code> or\n      <code>/[^0-9]/</code> matches \"B\" in \"B2 is the suite number\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\w</code></td>\n  <td>\n    <p>\n      Matches any alphanumeric character from the basic Latin alphabet,\n      including the underscore. Equivalent to <code>[A-Za-z0-9_]</code>. For\n      example, <code>/\\w/</code> matches \"a\" in \"apple\", \"5\" in \"$5.28\", and \"3\"\n      in \"3D\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\W</code></td>\n  <td>\n    <p>\n      Matches any character that is not a word character from the basic Latin\n      alphabet. Equivalent to <code>[^A-Za-z0-9_]</code>. For example,\n      <code>/\\W/</code> or <code>/[^A-Za-z0-9_]/</code> matches \"%\" in \"50%\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\s</code></td>\n  <td>\n    <p>\n      Matches a single white space character, including space, tab, form feed,\n      line feed, and other Unicode spaces. Equivalent to\n      <code\n        >[\n        \\f\\n\\r\\t\\v\\u00a0\\u1680\\u2000-\\u200a\\u2028\\u2029\\u202f\\u205f\\u3000\\ufeff]</code\n      >. For example, <code>/\\s\\w*/</code> matches \" bar\" in \"foo bar\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\S</code></td>\n  <td>\n    <p>\n      Matches a single character other than white space. Equivalent to\n      <code\n        >[^\n        \\f\\n\\r\\t\\v\\u00a0\\u1680\\u2000-\\u200a\\u2028\\u2029\\u202f\\u205f\\u3000\\ufeff]</code\n      >. For example, <code>/\\S\\w*/</code> matches \"foo\" in \"foo bar\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code>\\c<em>X</em></code>\n  </td>\n  <td>\n    <p>\n      Matches a control character using\n      <a href=\"https://en.wikipedia.org/wiki/Caret_notation\">caret notation</a>,\n      where \"X\" is a letter from A–Z (corresponding to codepoints\n      <code>U+0001</code><em>–</em><code>U+001F</code>). For example,\n      <code>/\\cM/</code> matches \"\\r\" in \"\\r\\n\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\</code></td>\n  <td>\n    <p>\n      Indicates that the following character should be treated specially, or\n      \"escaped\". It behaves one of two ways.\n    </p>\n    <ul>\n      <li>\n        For characters that are usually treated literally, indicates that the\n        next character is special and not to be interpreted literally. For\n        example, <code>/b/</code> matches the character \"b\". By placing a\n        backslash in front of \"b\", that is by using <code>/\\b/</code>, the\n        character becomes special to mean match a word boundary.\n      </li>\n      <li>\n        For characters that are usually treated specially, indicates that the\n        next character is not special and should be interpreted literally. For\n        example, \"*\" is a special character that means 0 or more occurrences of\n        the preceding character should be matched; for example,\n        <code>/a*/</code> means match 0 or more \"a\"s. To match\n        <code>*</code> literally, precede it with a backslash; for example,\n        <code>/a\\*/</code> matches \"a*\".\n      </li>\n    </ul>\n    <p>\n      Note that some characters like <code>:</code>, <code>-</code>,\n      <code>@</code>, etc. neither have a special meaning when escaped nor when\n      unescaped. Escape sequences like <code>\\:</code>, <code>\\-</code>,\n      <code>\\@</code> will be equivalent to their literal, unescaped character\n      equivalents in regular expressions. However, in regular expressions with\n      the\n      <a\n        href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions#advanced_searching_with_flags_2\"\n        >unicode flag</a\n      >, these will cause an <em>invalid identity escape</em> error. This is\n      done to ensure backward compatibility with existing code that uses new\n      escape sequences like <code>\\p</code> or <code>\\k</code>.\n    </p>\n    <div class=\"notecard note\">\n      <p>\n        <strong>Note:</strong> To match this character literally, escape it with\n        itself. In other words to search for <code>\\</code> use\n        <code>/\\\\/</code>.\n      </p>\n    </div>\n  </td>\n</tr>\n"
```
##### td (160:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "Matches the beginning of input. If the multiline flag is set to true, also matches immediately after a line break character. For example, "
  type: "inlineCode"
  value: "/^A/"
  type: "text"
  value: " does not match the \"A\" in \"an A\", but does match the first \"A\" in \"An A\".",type: "blockquote"
children:
  type: "paragraph"
  children:
    type: "strong"
    children:
      type: "text"
      value: "Note:"
    type: "text"
    value: " This character has a different meaning when it appears at the start of a "
    type: "link"
    title:

    url: "/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges"
    children:
      type: "text"
      value: "group"
    type: "text"
    value: "."
```
##### tr (158:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches the beginning of input. If the multiline flag is set to true, also\n    matches immediately after a line break character. For example,\n    <code>/^A/</code> does not match the \"A\" in \"an A\", but does match the first\n    \"A\" in \"An A\".\n  </p>\n  <div class=\"notecard note\">\n    <p>\n      <strong>Note:</strong> This character has a different meaning when it\n      appears at the start of a\n      <a\n        href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges\"\n        >group</a\n      >.\n    </p>\n  </div>\n</td>\n"
```
##### td (170:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 2
shouldWrap: true
children:
  type: "text"
  value: "Matches the end of input. If the multiline flag is set to true, also matches immediately before a line break character. For example, "
  type: "inlineCode"
  value: "/t$/"
  type: "text"
  value: " does not match the \"t\" in \"eater\", but does match it in \"eat\"."
```
##### tr (168:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches the end of input. If the multiline flag is set to true, also matches\n    immediately before a line break character. For example,\n    <code>/t$/</code> does not match the \"t\" in \"eater\", but does match it in\n    \"eat\".\n  </p>\n</td>\n"
```
##### td (176:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "Matches a word boundary. This is the position where a word character is not followed or preceded by another word-character, such as between a letter and a space. Note that a matched word boundary is not included in the match. In other words, the length of a matched word boundary is zero.",type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "Examples:",type: "list"
ordered: false
start:

spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "inlineCode"
      value: "/\\bm/"
      type: "text"
      value: " matches the \"m\" in \"moon\"."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "inlineCode"
      value: "/oo\\b/"
      type: "text"
      value: " does not match the \"oo\" in \"moon\", because \"oo\" is followed by \"n\" which is a word character."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "inlineCode"
      value: "/oon\\b/"
      type: "text"
      value: " matches the \"oon\" in \"moon\", because \"oon\" is the end of the string, thus not followed by a word character."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "inlineCode"
      value: "/\\w\\b\\w/"
      type: "text"
      value: " will never match anything, because a word character can never be followed by both a non-word and a word character.",type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "To match a backspace character ("
  type: "inlineCode"
  value: "[\\b]"
  type: "text"
  value: "), see "
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes"
  children:
    type: "text"
    value: "Character Classes"
  type: "text"
  value: "."
```
##### tr (174:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches a word boundary. This is the position where a word character is not\n    followed or preceded by another word-character, such as between a letter and\n    a space. Note that a matched word boundary is not included in the match. In\n    other words, the length of a matched word boundary is zero.\n  </p>\n  <p>Examples:</p>\n  <ul>\n    <li><code>/\\bm/</code> matches the \"m\" in \"moon\".</li>\n    <li>\n      <code>/oo\\b/</code> does not match the \"oo\" in \"moon\", because \"oo\" is\n      followed by \"n\" which is a word character.\n    </li>\n    <li>\n      <code>/oon\\b/</code> matches the \"oon\" in \"moon\", because \"oon\" is the end\n      of the string, thus not followed by a word character.\n    </li>\n    <li>\n      <code>/\\w\\b\\w/</code> will never match anything, because a word character\n      can never be followed by both a non-word and a word character.\n    </li>\n  </ul>\n  <p>\n    To match a backspace character (<code>[\\b]</code>), see\n    <a\n      href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes\"\n      >Character Classes</a\n    >.\n  </p>\n</td>\n"
```
##### td (193:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 4
shouldWrap: true
children:
  type: "text"
  value: "Matches a non-word boundary. This is a position where the previous and next character are of the same type: Either both must be words, or both must be non-words, for example between two letters or between two spaces. The beginning and end of a string are considered non-words. Same as the matched word boundary, the matched non-word boundary is also not included in the match. For example, "
  type: "inlineCode"
  value: "/\\Bon/"
  type: "text"
  value: " matches \"on\" in \"at noon\", and "
  type: "inlineCode"
  value: "/ye\\B/"
  type: "text"
  value: " matches \"ye\" in \"possibly yesterday\"."
```
##### tr (191:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches a non-word boundary. This is a position where the previous and next\n    character are of the same type: Either both must be words, or both must be\n    non-words, for example between two letters or between two spaces. The\n    beginning and end of a string are considered non-words. Same as the matched\n    word boundary, the matched non-word boundary is also not included in the\n    match. For example, <code>/\\Bon/</code> matches \"on\" in \"at noon\", and\n    <code>/ye\\B/</code> matches \"ye\" in \"possibly yesterday\".\n  </p>\n</td>\n"
```
##### table.standard-table (150:1) => table
```
type: "html"
value: "<tr>\n  <td><code>^</code></td>\n  <td>\n    <p>\n      Matches the beginning of input. If the multiline flag is set to true, also\n      matches immediately after a line break character. For example,\n      <code>/^A/</code> does not match the \"A\" in \"an A\", but does match the\n      first \"A\" in \"An A\".\n    </p>\n    <div class=\"notecard note\">\n      <p>\n        <strong>Note:</strong> This character has a different meaning when it\n        appears at the start of a\n        <a\n          href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges\"\n          >group</a\n        >.\n      </p>\n    </div>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>$</code></td>\n  <td>\n    <p>\n      Matches the end of input. If the multiline flag is set to true, also\n      matches immediately before a line break character. For example,\n      <code>/t$/</code> does not match the \"t\" in \"eater\", but does match it in\n      \"eat\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\b</code></td>\n  <td>\n    <p>\n      Matches a word boundary. This is the position where a word character is\n      not followed or preceded by another word-character, such as between a\n      letter and a space. Note that a matched word boundary is not included in\n      the match. In other words, the length of a matched word boundary is zero.\n    </p>\n    <p>Examples:</p>\n    <ul>\n      <li><code>/\\bm/</code> matches the \"m\" in \"moon\".</li>\n      <li>\n        <code>/oo\\b/</code> does not match the \"oo\" in \"moon\", because \"oo\" is\n        followed by \"n\" which is a word character.\n      </li>\n      <li>\n        <code>/oon\\b/</code> matches the \"oon\" in \"moon\", because \"oon\" is the\n        end of the string, thus not followed by a word character.\n      </li>\n      <li>\n        <code>/\\w\\b\\w/</code> will never match anything, because a word\n        character can never be followed by both a non-word and a word character.\n      </li>\n    </ul>\n    <p>\n      To match a backspace character (<code>[\\b]</code>), see\n      <a\n        href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes\"\n        >Character Classes</a\n      >.\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\B</code></td>\n  <td>\n    <p>\n      Matches a non-word boundary. This is a position where the previous and\n      next character are of the same type: Either both must be words, or both\n      must be non-words, for example between two letters or between two\n      spaces. The beginning and end of a string are considered non-words. Same\n      as the matched word boundary, the matched non-word boundary is also not\n      included in the match. For example, <code>/\\Bon/</code> matches \"on\" in\n      \"at noon\", and <code>/ye\\B/</code> matches \"ye\" in \"possibly yesterday\".\n    </p>\n  </td>\n</tr>\n"
```
##### td (216:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 1
shouldWrap: true
children:
  type: "strong"
  children:
    type: "text"
    value: "Lookahead assertion:"
  type: "text"
  value: " "
  type: "text"
  value: "Matches \"x\" only if \"x\" is followed by \"y\". For example, /"
  type: "inlineCode"
  value: "Jack(?=Sprat)/"
  type: "text"
  value: " matches \"Jack\" only if it is followed by \"Sprat\"."
  type: "break"
  type: "inlineCode"
  value: "/Jack(?=Sprat|Frost)/"
  type: "text"
  value: " matches \"Jack\" only if it is followed by \"Sprat\" or \"Frost\". However, neither \"Sprat\" nor \"Frost\" is part of the match results."
```
##### tr (214:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <strong>Lookahead assertion: </strong>Matches \"x\" only if \"x\" is followed by\n    \"y\". For example, /<code>Jack(?=Sprat)/</code> matches \"Jack\" only if it is\n    followed by \"Sprat\".<br /><code>/Jack(?=Sprat|Frost)/</code> matches \"Jack\"\n    only if it is followed by \"Sprat\" or \"Frost\". However, neither \"Sprat\" nor\n    \"Frost\" is part of the match results.\n  </p>\n</td>\n"
```
##### td (223:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 2
shouldWrap: true
children:
  type: "strong"
  children:
    type: "text"
    value: "Negative lookahead assertion:"
  type: "text"
  value: " "
  type: "text"
  value: "Matches \"x\" only if \"x\" is not followed by \"y\". For example, "
  type: "inlineCode"
  value: "/\\d+(?!\\.)/"
  type: "text"
  value: " matches a number only if it is not followed by a decimal point. "
  type: "inlineCode"
  value: "/\\d+(?!\\.)/.exec('3.141')"
  type: "text"
  value: " matches \"141\" but not \"3\"."
```
##### tr (221:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <strong>Negative lookahead assertion: </strong>Matches \"x\" only if \"x\" is\n    not followed by \"y\". For example, <code>/\\d+(?!\\.)/</code> matches a number\n    only if it is not followed by a decimal point. <code\n      >/\\d+(?!\\.)/.exec('3.141')</code\n    >\n    matches \"141\" but not \"3\".\n  </p>\n</td>\n"
```
##### td (229:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 3
shouldWrap: true
children:
  type: "strong"
  children:
    type: "text"
    value: "Lookbehind assertion:"
  type: "text"
  value: " "
  type: "text"
  value: "Matches \"x\" only if \"x\" is preceded by \"y\". For example, "
  type: "inlineCode"
  value: "/(?<=Jack)Sprat/"
  type: "text"
  value: " matches \"Sprat\" only if it is preceded by \"Jack\". "
  type: "inlineCode"
  value: "/(?<=Jack|Tom)Sprat/"
  type: "text"
  value: " matches \"Sprat\" only if it is preceded by \"Jack\" or \"Tom\". However, neither \"Jack\" nor \"Tom\" is part of the match results."
```
##### tr (227:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <strong>Lookbehind assertion: </strong>Matches \"x\" only if \"x\" is\n    preceded by \"y\". For example, <code>/(?&#x3C;=Jack)Sprat/</code> matches\n    \"Sprat\" only if it is preceded by \"Jack\". <code\n      >/(?&#x3C;=Jack|Tom)Sprat/</code\n    >\n    matches \"Sprat\" only if it is preceded by \"Jack\" or \"Tom\". However, neither\n    \"Jack\" nor \"Tom\" is part of the match results.\n  </p>\n</td>\n"
```
##### td (235:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 4
shouldWrap: true
children:
  type: "strong"
  children:
    type: "text"
    value: "Negative lookbehind assertion:"
  type: "text"
  value: " "
  type: "text"
  value: "Matches \"x\" only if \"x\" is not preceded by \"y\". For example, "
  type: "inlineCode"
  value: "/(?<!-)\\d+/"
  type: "text"
  value: " matches a number only if it is not preceded by a minus sign. "
  type: "inlineCode"
  value: "/(?<!-)\\d+/.exec('3')"
  type: "text"
  value: " matches \"3\". "
  type: "inlineCode"
  value: "/(?<!-)\\d+/.exec('-3')"
  type: "text"
  value: "  match is not found because the number is preceded by the minus sign."
```
##### tr (233:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <strong>Negative lookbehind assertion: </strong>Matches \"x\" only if \"x\" is\n    not preceded by \"y\". For example, <code>/(?&#x3C;!-)\\d+/</code> matches a\n    number only if it is not preceded by a minus sign. <code\n      >/(?&#x3C;!-)\\d+/.exec('3')</code\n    >\n    matches \"3\". <code>/(?&#x3C;!-)\\d+/.exec('-3')</code>  match is not found\n    because the number is preceded by the minus sign.\n  </p>\n</td>\n"
```
##### table.standard-table (206:1) => table
```
type: "html"
value: "<tr>\n  <td><code>x(?=y)</code></td>\n  <td>\n    <p>\n      <strong>Lookahead assertion: </strong>Matches \"x\" only if \"x\" is followed\n      by \"y\". For example, /<code>Jack(?=Sprat)/</code> matches \"Jack\" only if\n      it is followed by \"Sprat\".<br /><code>/Jack(?=Sprat|Frost)/</code> matches\n      \"Jack\" only if it is followed by \"Sprat\" or \"Frost\". However, neither\n      \"Sprat\" nor \"Frost\" is part of the match results.\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>x(?!y)</code></td>\n  <td>\n    <p>\n      <strong>Negative lookahead assertion: </strong>Matches \"x\" only if \"x\" is\n      not followed by \"y\". For example, <code>/\\d+(?!\\.)/</code> matches a\n      number only if it is not followed by a decimal point. <code\n        >/\\d+(?!\\.)/.exec('3.141')</code\n      >\n      matches \"141\" but not \"3\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>(?&#x3C;=y)x</code></td>\n  <td>\n    <p>\n      <strong>Lookbehind assertion: </strong>Matches \"x\" only if \"x\" is\n      preceded by \"y\". For example, <code>/(?&#x3C;=Jack)Sprat/</code> matches\n      \"Sprat\" only if it is preceded by \"Jack\". <code\n        >/(?&#x3C;=Jack|Tom)Sprat/</code\n      >\n      matches \"Sprat\" only if it is preceded by \"Jack\" or \"Tom\". However,\n      neither \"Jack\" nor \"Tom\" is part of the match results.\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>(?&#x3C;!y)x</code></td>\n  <td>\n    <p>\n      <strong>Negative lookbehind assertion: </strong>Matches \"x\" only if \"x\" is\n      not preceded by \"y\". For example, <code>/(?&#x3C;!-)\\d+/</code> matches a\n      number only if it is not preceded by a minus sign. <code\n        >/(?&#x3C;!-)\\d+/.exec('3')</code\n      >\n      matches \"3\". <code>/(?&#x3C;!-)\\d+/.exec('-3')</code>  match is not found\n      because the number is preceded by the minus sign.\n    </p>\n  </td>\n</tr>\n"
```
##### td (255:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "Matches either \"x\" or \"y\". For example, "
  type: "inlineCode"
  value: "/green|red/"
  type: "text"
  value: " matches \"green\" in \"green apple\" and \"red\" in \"red apple\"."
```
##### tr (253:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches either \"x\" or \"y\". For example, <code>/green|red/</code> matches\n    \"green\" in \"green apple\" and \"red\" in \"red apple\".\n  </p>\n</td>\n"
```
##### td (262:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 2
shouldWrap: true
children:
  type: "text"
  value: "A character class. Matches any one of the enclosed characters. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets it is taken as a literal hyphen to be included in the character class as a normal character.",type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 2
shouldWrap: true
children:
  type: "text"
  value: "For example, "
  type: "inlineCode"
  value: "[abcd]"
  type: "text"
  value: " is the same as "
  type: "inlineCode"
  value: "[a-d]"
  type: "text"
  value: ". They match the \"b\" in \"brisket\", and the \"c\" in \"chop\".",type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 2
shouldWrap: true
children:
  type: "text"
  value: "For example, "
  type: "inlineCode"
  value: "[abcd-]"
  type: "text"
  value: " and "
  type: "inlineCode"
  value: "[-abcd]"
  type: "text"
  value: " match the \"b\" in \"brisket\", the \"c\" in \"chop\", and the \"-\" (hyphen) in \"non-profit\".",type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 2
shouldWrap: true
children:
  type: "text"
  value: "For example, "
  type: "inlineCode"
  value: "[\\w-]"
  type: "text"
  value: " is the same as "
  type: "inlineCode"
  value: "[A-Za-z0-9_-]"
  type: "text"
  value: ". They both match the \"b\" in \"brisket\", the \"c\" in \"chop\", and the \"n\" in \"non-profit\"."
```
##### tr (259:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    A character class. Matches any one of the enclosed characters. You can\n    specify a range of characters by using a hyphen, but if the hyphen appears\n    as the first or last character enclosed in the square brackets it is taken\n    as a literal hyphen to be included in the character class as a normal\n    character.\n  </p>\n  <p>\n    For example, <code>[abcd]</code> is the same as <code>[a-d]</code>. They\n    match the \"b\" in \"brisket\", and the \"c\" in \"chop\".\n  </p>\n  <p>\n    For example, <code>[abcd-]</code> and <code>[-abcd]</code> match the \"b\" in\n    \"brisket\", the \"c\" in \"chop\", and the \"-\" (hyphen) in \"non-profit\".\n  </p>\n  <p>\n    For example, <code>[\\w-]</code> is the same as <code>[A-Za-z0-9_-]</code>.\n    They both match the \"b\" in \"brisket\", the \"c\" in \"chop\", and the \"n\" in\n    \"non-profit\".\n  </p>\n</td>\n"
```
##### td (273:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 3
shouldWrap: true
children:
  type: "inlineCode"
  value: "[^xyz] [^a-c]"
```
##### td (277:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "A negated or complemented character class. That is, it matches anything that is not enclosed in the brackets. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets it is taken as a literal hyphen to be included in the character class as a normal character. For example, "
  type: "inlineCode"
  value: "[^abc]"
  type: "text"
  value: " is the same as "
  type: "inlineCode"
  value: "[^a-c]"
  type: "text"
  value: ". They initially match \"o\" in \"bacon\" and \"h\" in \"chop\".",type: "blockquote"
children:
  type: "paragraph"
  children:
    type: "strong"
    children:
      type: "text"
      value: "Note:"
    type: "text"
    value: " The ^ character may also indicate the "
    type: "link"
    title:

    url: "/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions"
    children:
      type: "text"
      value: "beginning of input"
    type: "text"
    value: "."
```
##### tr (272:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <code>[^xyz]<br />[^a-c]</code>\n  </p>\n</td>\n",type: "html"
value: "<td>\n  <p>\n    A negated or complemented character class. That is, it matches anything that\n    is not enclosed in the brackets. You can specify a range of characters by\n    using a hyphen, but if the hyphen appears as the first or last character\n    enclosed in the square brackets it is taken as a literal hyphen to be\n    included in the character class as a normal character. For example,\n    <code>[^abc]</code> is the same as <code>[^a-c]</code>. They initially match\n    \"o\" in \"bacon\" and \"h\" in \"chop\".\n  </p>\n  <div class=\"notecard note\">\n    <p>\n      <strong>Note:</strong> The ^ character may also indicate the\n      <a href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions\"\n        >beginning of input</a\n      >.\n    </p>\n  </div>\n</td>\n"
```
##### td (287:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 4
shouldWrap: true
children:
  type: "strong"
  children:
    type: "text"
    value: "Capturing group:"
  type: "text"
  value: " "
  type: "text"
  value: "Matches "
  type: "inlineCode"
  value: "x"
  type: "text"
  value: " and remembers the match. For example, "
  type: "inlineCode"
  value: "/(foo)/"
  type: "text"
  value: " matches and remembers \"foo\" in \"foo bar\". ",type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 4
shouldWrap: true
children:
  type: "text"
  value: "A regular expression may have multiple capturing groups. In results, matches to capturing groups typically in an array whose members are in the same order as the left parentheses in the capturing group. This is usually just the order of the capturing groups themselves. This becomes important when capturing groups are nested. Matches are accessed using the index of the result's elements ("
  type: "inlineCode"
  value: "[1], ..., [n]"
  type: "text"
  value: ") or from the predefined "
  type: "inlineCode"
  value: "RegExp"
  type: "text"
  value: " object's properties ("
  type: "inlineCode"
  value: "$1, ..., $9"
  type: "text"
  value: ").",type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 4
shouldWrap: true
children:
  type: "text"
  value: "Capturing groups have a performance penalty. If you don't need the matched substring to be recalled, prefer non-capturing parentheses (see below).",type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 4
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match"
  children:
    type: "inlineCode"
    value: "String.match()"
  type: "text"
  value: " won't return groups if the "
  type: "inlineCode"
  value: "/.../g"
  type: "text"
  value: " flag is set. However, you can still use "
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/matchAll"
  children:
    type: "inlineCode"
    value: "String.matchAll()"
  type: "text"
  value: " to get all matches."
```
##### tr (285:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <strong>Capturing group: </strong>Matches <code><em>x</em></code> and\n    remembers the match. For example, <code>/(foo)/</code> matches and remembers\n    \"foo\" in \"foo bar\". \n  </p>\n  <p>\n    A regular expression may have multiple capturing groups. In results, matches\n    to capturing groups typically in an array whose members are in the same\n    order as the left parentheses in the capturing group. This is usually just\n    the order of the capturing groups themselves. This becomes important when\n    capturing groups are nested. Matches are accessed using the index of the\n    result's elements (<code>[1], ..., [n]</code>) or from the predefined\n    <code>RegExp</code> object's properties (<code>$1, ..., $9</code>).\n  </p>\n  <p>\n    Capturing groups have a performance penalty. If you don't need the matched\n    substring to be recalled, prefer non-capturing parentheses (see below).\n  </p>\n  <p>\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match\"\n        >String.match()</a\n      ></code\n    >\n    won't return groups if the <code>/.../g</code> flag is set. However, you can\n    still use\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/matchAll\"\n        >String.matchAll()</a\n      ></code\n    >\n    to get all matches.\n  </p>\n</td>\n"
```
##### td (299:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 5
shouldWrap: true
children:
  type: "text"
  value: "Where \"n\" is a positive integer. A back reference to the last substring matching the n parenthetical in the regular expression (counting left parentheses). For example, "
  type: "inlineCode"
  value: "/apple(,)\\sorange\\1/"
  type: "text"
  value: " matches \"apple, orange,\" in \"apple, orange, cherry, peach\"."
```
##### tr (297:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Where \"n\" is a positive integer. A back reference to the last substring\n    matching the n parenthetical in the regular expression (counting left\n    parentheses). For example, <code>/apple(,)\\sorange\\1/</code> matches \"apple,\n    orange,\" in \"apple, orange, cherry, peach\".\n  </p>\n</td>\n"
```
##### td (305:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 6
shouldWrap: true
children:
  type: "text"
  value: "A back reference to the last substring matching the "
  type: "strong"
  children:
    type: "text"
    value: "Named capture group"
  type: "text"
  value: " "
  type: "text"
  value: "specified by "
  type: "inlineCode"
  value: "<Name>"
  type: "text"
  value: ".",type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 6
shouldWrap: true
children:
  type: "text"
  value: "For example, "
  type: "inlineCode"
  value: "/(?<title>\\w+), yes \\k<title>/"
  type: "text"
  value: " matches \"Sir, yes Sir\" in \"Do you copy? Sir, yes Sir!\".",type: "blockquote"
children:
  type: "paragraph"
  children:
    type: "strong"
    children:
      type: "text"
      value: "Note:"
    type: "text"
    value: " "
    type: "inlineCode"
    value: "\\k"
    type: "text"
    value: " is used literally here to indicate the beginning of a back reference to a Named capture group."
```
##### tr (303:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    A back reference to the last substring matching the <strong\n      >Named capture group </strong\n    >specified by <code>&#x3C;Name></code>.\n  </p>\n  <p>\n    For example, <code>/(?&#x3C;title>\\w+), yes \\k&#x3C;title>/</code> matches\n    \"Sir, yes Sir\" in \"Do you copy? Sir, yes Sir!\".\n  </p>\n  <div class=\"notecard note\">\n    <p>\n      <strong>Note:</strong> <code>\\k</code> is used literally here to indicate\n      the beginning of a back reference to a Named capture group.\n    </p>\n  </div>\n</td>\n"
```
##### td (317:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 7
shouldWrap: true
children:
  type: "strong"
  children:
    type: "text"
    value: "Named capturing group:"
  type: "text"
  value: " "
  type: "text"
  value: "Matches \"x\" and stores it on the groups property of the returned matches under the name specified by "
  type: "inlineCode"
  value: "<Name>"
  type: "text"
  value: ". The angle brackets ("
  type: "inlineCode"
  value: "<"
  type: "text"
  value: " and "
  type: "inlineCode"
  value: ">"
  type: "text"
  value: ") are required for group name.",type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 7
shouldWrap: true
children:
  type: "text"
  value: "For example, to extract the United States area code from a phone number, we could use "
  type: "inlineCode"
  value: "/\\((?<area>\\d\\d\\d)\\)/"
  type: "text"
  value: ". The resulting number would appear under "
  type: "inlineCode"
  value: "matches.groups.area"
  type: "text"
  value: "."
```
##### tr (315:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <strong>Named capturing group: </strong>Matches \"x\" and stores it on the\n    groups property of the returned matches under the name specified by\n    <code>&#x3C;Name></code>. The angle brackets (<code>&#x3C;</code> and\n    <code>></code>) are required for group name.\n  </p>\n  <p>\n    For example, to extract the United States area code from a phone number, we\n    could use <code>/\\((?&#x3C;area>\\d\\d\\d)\\)/</code>. The resulting number\n    would appear under <code>matches.groups.area</code>.\n  </p>\n</td>\n"
```
##### table.standard-table (245:1) => table
```
type: "html"
value: "<tr>\n  <td>\n    <code><em>x</em>|<em>y</em></code>\n  </td>\n  <td>\n    <p>\n      Matches either \"x\" or \"y\". For example, <code>/green|red/</code> matches\n      \"green\" in \"green apple\" and \"red\" in \"red apple\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code>[xyz]<br />[a-c]</code>\n  </td>\n  <td>\n    <p>\n      A character class. Matches any one of the enclosed characters. You can\n      specify a range of characters by using a hyphen, but if the hyphen appears\n      as the first or last character enclosed in the square brackets it is taken\n      as a literal hyphen to be included in the character class as a normal\n      character.\n    </p>\n    <p>\n      For example, <code>[abcd]</code> is the same as <code>[a-d]</code>. They\n      match the \"b\" in \"brisket\", and the \"c\" in \"chop\".\n    </p>\n    <p>\n      For example, <code>[abcd-]</code> and <code>[-abcd]</code> match the \"b\"\n      in \"brisket\", the \"c\" in \"chop\", and the \"-\" (hyphen) in \"non-profit\".\n    </p>\n    <p>\n      For example, <code>[\\w-]</code> is the same as <code>[A-Za-z0-9_-]</code>.\n      They both match the \"b\" in \"brisket\", the \"c\" in \"chop\", and the \"n\" in\n      \"non-profit\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <p>\n      <code>[^xyz]<br />[^a-c]</code>\n    </p>\n  </td>\n  <td>\n    <p>\n      A negated or complemented character class. That is, it matches anything\n      that is not enclosed in the brackets. You can specify a range of\n      characters by using a hyphen, but if the hyphen appears as the first or\n      last character enclosed in the square brackets it is taken as a literal\n      hyphen to be included in the character class as a normal character. For\n      example, <code>[^abc]</code> is the same as <code>[^a-c]</code>. They\n      initially match \"o\" in \"bacon\" and \"h\" in \"chop\".\n    </p>\n    <div class=\"notecard note\">\n      <p>\n        <strong>Note:</strong> The ^ character may also indicate the\n        <a\n          href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions\"\n          >beginning of input</a\n        >.\n      </p>\n    </div>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>(<em>x</em>)</code></td>\n  <td>\n    <p>\n      <strong>Capturing group: </strong>Matches <code><em>x</em></code> and\n      remembers the match. For example, <code>/(foo)/</code> matches and\n      remembers \"foo\" in \"foo bar\". \n    </p>\n    <p>\n      A regular expression may have multiple capturing groups. In results,\n      matches to capturing groups typically in an array whose members are in the\n      same order as the left parentheses in the capturing group. This is usually\n      just the order of the capturing groups themselves. This becomes important\n      when capturing groups are nested. Matches are accessed using the index of\n      the result's elements (<code>[1], ..., [n]</code>) or from the predefined\n      <code>RegExp</code> object's properties (<code>$1, ..., $9</code>).\n    </p>\n    <p>\n      Capturing groups have a performance penalty. If you don't need the matched\n      substring to be recalled, prefer non-capturing parentheses (see below).\n    </p>\n    <p>\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match\"\n          >String.match()</a\n        ></code\n      >\n      won't return groups if the <code>/.../g</code> flag is set. However, you\n      can still use\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/matchAll\"\n          >String.matchAll()</a\n        ></code\n      >\n      to get all matches.\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code>\\<em>n</em></code>\n  </td>\n  <td>\n    <p>\n      Where \"n\" is a positive integer. A back reference to the last substring\n      matching the n parenthetical in the regular expression (counting left\n      parentheses). For example, <code>/apple(,)\\sorange\\1/</code> matches\n      \"apple, orange,\" in \"apple, orange, cherry, peach\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\\k&#x3C;Name></td>\n  <td>\n    <p>\n      A back reference to the last substring matching the <strong\n        >Named capture group </strong\n      >specified by <code>&#x3C;Name></code>.\n    </p>\n    <p>\n      For example, <code>/(?&#x3C;title>\\w+), yes \\k&#x3C;title>/</code> matches\n      \"Sir, yes Sir\" in \"Do you copy? Sir, yes Sir!\".\n    </p>\n    <div class=\"notecard note\">\n      <p>\n        <strong>Note:</strong> <code>\\k</code> is used literally here to\n        indicate the beginning of a back reference to a Named capture group.\n      </p>\n    </div>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>(?&#x3C;Name>x)</code></td>\n  <td>\n    <p>\n      <strong>Named capturing group: </strong>Matches \"x\" and stores it on the\n      groups property of the returned matches under the name specified by\n      <code>&#x3C;Name></code>. The angle brackets (<code>&#x3C;</code> and\n      <code>></code>) are required for group name.\n    </p>\n    <p>\n      For example, to extract the United States area code from a phone number,\n      we could use <code>/\\((?&#x3C;area>\\d\\d\\d)\\)/</code>. The resulting number\n      would appear under <code>matches.groups.area</code>.\n    </p>\n  </td>\n</tr>\n"
```
##### td (347:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "Matches the preceding item \"x\" 0 or more times. For example, "
  type: "inlineCode"
  value: "/bo*/"
  type: "text"
  value: " matches \"boooo\" in \"A ghost booooed\" and \"b\" in \"A bird warbled\", but nothing in \"A goat grunted\"."
```
##### tr (345:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches the preceding item \"x\" 0 or more times. For example,\n    <code>/bo*/</code> matches \"boooo\" in \"A ghost booooed\" and \"b\" in \"A bird\n    warbled\", but nothing in \"A goat grunted\".\n  </p>\n</td>\n"
```
##### td (353:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 2
shouldWrap: true
children:
  type: "text"
  value: "Matches the preceding item \"x\" 1 or more times. Equivalent to "
  type: "inlineCode"
  value: "{1,}"
  type: "text"
  value: ". For example, "
  type: "inlineCode"
  value: "/a+/"
  type: "text"
  value: " matches the \"a\" in \"candy\" and all the \"a\"'s in \"caaaaaaandy\"."
```
##### tr (351:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches the preceding item \"x\" 1 or more times. Equivalent to\n    <code>{1,}</code>. For example, <code>/a+/</code> matches the \"a\" in \"candy\"\n    and all the \"a\"'s in \"caaaaaaandy\".\n  </p>\n</td>\n"
```
##### td (359:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "Matches the preceding item \"x\" 0 or 1 times. For example, "
  type: "inlineCode"
  value: "/e?le?/"
  type: "text"
  value: " matches the \"el\" in \"angel\" and the \"le\" in \"angle.\"",type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "If used immediately after any of the quantifiers "
  type: "inlineCode"
  value: "*"
  type: "text"
  value: ", "
  type: "inlineCode"
  value: "+"
  type: "text"
  value: ", "
  type: "inlineCode"
  value: "?"
  type: "text"
  value: ", or "
  type: "inlineCode"
  value: "{}"
  type: "text"
  value: ", makes the quantifier non-greedy (matching the minimum number of times), as opposed to the default, which is greedy (matching the maximum number of times)."
```
##### tr (357:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches the preceding item \"x\" 0 or 1 times. For example,\n    <code>/e?le?/</code> matches the \"el\" in \"angel\" and the \"le\" in \"angle.\"\n  </p>\n  <p>\n    If used immediately after any of the quantifiers <code>*</code>,\n    <code>+</code>, <code>?</code>, or <code>{}</code>, makes the quantifier\n    non-greedy (matching the minimum number of times), as opposed to the\n    default, which is greedy (matching the maximum number of times).\n  </p>\n</td>\n"
```
##### td (367:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 4
shouldWrap: true
children:
  type: "text"
  value: "Where \"n\" is a positive integer, matches exactly \"n\" occurrences of the preceding item \"x\". For example, "
  type: "inlineCode"
  value: "/a{2}/"
  type: "text"
  value: " doesn't match the \"a\" in \"candy\", but it matches all of the \"a\"'s in \"caandy\", and the first two \"a\"'s in \"caaandy\"."
```
##### tr (365:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Where \"n\" is a positive integer, matches exactly \"n\" occurrences of the\n    preceding item \"x\". For example, <code>/a{2}/</code> doesn't match the \"a\"\n    in \"candy\", but it matches all of the \"a\"'s in \"caandy\", and the first two\n    \"a\"'s in \"caaandy\".\n  </p>\n</td>\n"
```
##### td (373:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 5
shouldWrap: true
children:
  type: "text"
  value: "Where \"n\" is a positive integer, matches at least \"n\" occurrences of the preceding item \"x\". For example, "
  type: "inlineCode"
  value: "/a{2,}/"
  type: "text"
  value: " doesn't match the \"a\" in \"candy\", but matches all of the a's in \"caandy\" and in \"caaaaaaandy\"."
```
##### tr (371:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Where \"n\" is a positive integer, matches at least \"n\" occurrences of the\n    preceding item \"x\". For example, <code>/a{2,}/</code> doesn't match the \"a\"\n    in \"candy\", but matches all of the a's in \"caandy\" and in \"caaaaaaandy\".\n  </p>\n</td>\n"
```
##### td (379:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 6
shouldWrap: true
children:
  type: "text"
  value: "Where \"n\" is 0 or a positive integer, \"m\" is a positive integer, and "
  type: "inlineCode"
  value: "m > n"
  type: "text"
  value: ", matches at least \"n\" and at most \"m\" occurrences of the preceding item \"x\". For example, "
  type: "inlineCode"
  value: "/a{1,3}/"
  type: "text"
  value: " matches nothing in \"cndy\", the \"a\" in \"candy\", the two \"a\"'s in \"caandy\", and the first three \"a\"'s in \"caaaaaaandy\". Notice that when matching \"caaaaaaandy\", the match is \"aaa\", even though the original string had more \"a\"s in it."
```
##### tr (377:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Where \"n\" is 0 or a positive integer, \"m\" is a positive integer, and\n    <code><em>m</em> > <em>n</em></code\n    >, matches at least \"n\" and at most \"m\" occurrences of the preceding item\n    \"x\". For example, <code>/a{1,3}/</code> matches nothing in \"cndy\", the \"a\"\n    in \"candy\", the two \"a\"'s in \"caandy\", and the first three \"a\"'s in\n    \"caaaaaaandy\". Notice that when matching \"caaaaaaandy\", the match is \"aaa\",\n    even though the original string had more \"a\"s in it.\n  </p>\n</td>\n"
```
##### td (384:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 7
shouldWrap: true
children:
  type: "inlineCode"
  value: "x*?"
  type: "break"
  type: "inlineCode"
  value: "x+?"
  type: "break"
  type: "inlineCode"
  value: "x??"
  type: "break"
  type: "inlineCode"
  value: "x{n}?"
  type: "break"
  type: "inlineCode"
  value: "x{n,}?"
  type: "break"
  type: "inlineCode"
  value: "x{n,m}?"
```
##### td (392:4) => tableCell
```
type: "paragraph"
summary: "This page provides an overall cheat sheet of all the capabilities of RegExp syntax by aggregating the content of the articles in the RegExp guide. If you need more information on a specific topic, please follow the link on the corresponding heading to access the full article or head to the guide."
rowIndex: 7
shouldWrap: true
children:
  type: "text"
  value: "By default quantifiers like "
  type: "inlineCode"
  value: "*"
  type: "text"
  value: " and "
  type: "inlineCode"
  value: "+"
  type: "text"
  value: " are \"greedy\", meaning that they try to match as much of the string as possible. The "
  type: "inlineCode"
  value: "?"
  type: "text"
  value: " character after the quantifier makes the quantifier \"non-greedy\": meaning that it will stop as soon as it finds a match. For example, given a string like \"some <foo> <bar> new </bar> </foo> thing\":",type: "list"
ordered: false
start:

spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "inlineCode"
      value: "/<.*>/"
      type: "text"
      value: " will match \"<foo> <bar> new </bar> </foo>\""
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "inlineCode"
      value: "/<.*?>/"
      type: "text"
      value: " will match \"<foo>\""
```
##### tr (383:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <code><em>x</em>*?</code><br /><code><em>x</em>+?</code><br /><code\n      ><em>x</em>??</code\n    ><br /><code><em>x</em>{n}?</code><br /><code><em>x</em>{n,}?</code\n    ><br /><code><em>x</em>{n,m}?</code>\n  </p>\n</td>\n",type: "html"
value: "<td>\n  <p>\n    By default quantifiers like <code>*</code> and <code>+</code> are \"greedy\",\n    meaning that they try to match as much of the string as possible. The\n    <code>?</code> character after the quantifier makes the quantifier\n    \"non-greedy\": meaning that it will stop as soon as it finds a match. For\n    example, given a string like \"some &#x3C;foo> &#x3C;bar> new &#x3C;/bar>\n    &#x3C;/foo> thing\":\n  </p>\n  <ul>\n    <li>\n      <code>/&#x3C;.*>/</code> will match \"&#x3C;foo> &#x3C;bar> new &#x3C;/bar>\n      &#x3C;/foo>\"\n    </li>\n    <li><code>/&#x3C;.*?>/</code> will match \"&#x3C;foo>\"</li>\n  </ul>\n</td>\n"
```
##### table.standard-table (337:1) => table
```
type: "html"
value: "<tr>\n  <td>\n    <code><em>x</em>*</code>\n  </td>\n  <td>\n    <p>\n      Matches the preceding item \"x\" 0 or more times. For example,\n      <code>/bo*/</code> matches \"boooo\" in \"A ghost booooed\" and \"b\" in \"A bird\n      warbled\", but nothing in \"A goat grunted\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code><em>x</em>+</code>\n  </td>\n  <td>\n    <p>\n      Matches the preceding item \"x\" 1 or more times. Equivalent to\n      <code>{1,}</code>. For example, <code>/a+/</code> matches the \"a\" in\n      \"candy\" and all the \"a\"'s in \"caaaaaaandy\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code><em>x</em>?</code>\n  </td>\n  <td>\n    <p>\n      Matches the preceding item \"x\" 0 or 1 times. For example,\n      <code>/e?le?/</code> matches the \"el\" in \"angel\" and the \"le\" in \"angle.\"\n    </p>\n    <p>\n      If used immediately after any of the quantifiers <code>*</code>,\n      <code>+</code>, <code>?</code>, or <code>{}</code>, makes the quantifier\n      non-greedy (matching the minimum number of times), as opposed to the\n      default, which is greedy (matching the maximum number of times).\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code><em>x</em>{<em>n</em>}</code>\n  </td>\n  <td>\n    <p>\n      Where \"n\" is a positive integer, matches exactly \"n\" occurrences of the\n      preceding item \"x\". For example, <code>/a{2}/</code> doesn't match the \"a\"\n      in \"candy\", but it matches all of the \"a\"'s in \"caandy\", and the first two\n      \"a\"'s in \"caaandy\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code><em>x</em>{<em>n</em>,}</code>\n  </td>\n  <td>\n    <p>\n      Where \"n\" is a positive integer, matches at least \"n\" occurrences of the\n      preceding item \"x\". For example, <code>/a{2,}/</code> doesn't match the\n      \"a\" in \"candy\", but matches all of the a's in \"caandy\" and in\n      \"caaaaaaandy\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code><em>x</em>{<em>n</em>,<em>m</em>}</code>\n  </td>\n  <td>\n    <p>\n      Where \"n\" is 0 or a positive integer, \"m\" is a positive integer, and\n      <code><em>m</em> > <em>n</em></code\n      >, matches at least \"n\" and at most \"m\" occurrences of the preceding item\n      \"x\". For example, <code>/a{1,3}/</code> matches nothing in \"cndy\", the \"a\"\n      in \"candy\", the two \"a\"'s in \"caandy\", and the first three \"a\"'s in\n      \"caaaaaaandy\". Notice that when matching \"caaaaaaandy\", the match is\n      \"aaa\", even though the original string had more \"a\"s in it.\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <p>\n      <code><em>x</em>*?</code><br /><code><em>x</em>+?</code><br /><code\n        ><em>x</em>??</code\n      ><br /><code><em>x</em>{n}?</code><br /><code><em>x</em>{n,}?</code\n      ><br /><code><em>x</em>{n,m}?</code>\n    </p>\n  </td>\n  <td>\n    <p>\n      By default quantifiers like <code>*</code> and <code>+</code> are\n      \"greedy\", meaning that they try to match as much of the string as\n      possible. The <code>?</code> character after the quantifier makes the\n      quantifier \"non-greedy\": meaning that it will stop as soon as it finds a\n      match. For example, given a string like \"some &#x3C;foo> &#x3C;bar> new\n      &#x3C;/bar> &#x3C;/foo> thing\":\n    </p>\n    <ul>\n      <li>\n        <code>/&#x3C;.*>/</code> will match \"&#x3C;foo> &#x3C;bar> new\n        &#x3C;/bar> &#x3C;/foo>\"\n      </li>\n      <li><code>/&#x3C;.*?>/</code> will match \"&#x3C;foo>\"</li>\n    </ul>\n  </td>\n</tr>\n"
```
### [/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges)
#### Invalid AST transformations
##### td (33:4) => tableCell
```
type: "paragraph"
summary: "Groups and ranges indicate groups and ranges of expression characters."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "Matches either \"x\" or \"y\". For example, "
  type: "inlineCode"
  value: "/green|red/"
  type: "text"
  value: " matches \"green\" in \"green apple\" and \"red\" in \"red apple\"."
```
##### tr (31:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches either \"x\" or \"y\". For example, <code>/green|red/</code> matches\n    \"green\" in \"green apple\" and \"red\" in \"red apple\".\n  </p>\n</td>\n"
```
##### td (40:4) => tableCell
```
type: "paragraph"
summary: "Groups and ranges indicate groups and ranges of expression characters."
rowIndex: 2
shouldWrap: true
children:
  type: "text"
  value: "A character class. Matches any one of the enclosed characters. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets it is taken as a literal hyphen to be included in the character class as a normal character.",type: "paragraph"
summary: "Groups and ranges indicate groups and ranges of expression characters."
rowIndex: 2
shouldWrap: true
children:
  type: "text"
  value: "For example, "
  type: "inlineCode"
  value: "[abcd]"
  type: "text"
  value: " is the same as "
  type: "inlineCode"
  value: "[a-d]"
  type: "text"
  value: ". They match the \"b\" in \"brisket\", and the \"c\" in \"chop\".",type: "paragraph"
summary: "Groups and ranges indicate groups and ranges of expression characters."
rowIndex: 2
shouldWrap: true
children:
  type: "text"
  value: "For example, "
  type: "inlineCode"
  value: "[abcd-]"
  type: "text"
  value: " and "
  type: "inlineCode"
  value: "[-abcd]"
  type: "text"
  value: " match the \"b\" in \"brisket\", the \"c\" in \"chop\", and the \"-\" (hyphen) in \"non-profit\".",type: "paragraph"
summary: "Groups and ranges indicate groups and ranges of expression characters."
rowIndex: 2
shouldWrap: true
children:
  type: "text"
  value: "For example, "
  type: "inlineCode"
  value: "[\\w-]"
  type: "text"
  value: " is the same as "
  type: "inlineCode"
  value: "[A-Za-z0-9_-]"
  type: "text"
  value: ". They both match the \"b\" in \"brisket\", the \"c\" in \"chop\", and the \"n\" in \"non-profit\"."
```
##### tr (37:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    A character class. Matches any one of the enclosed characters. You can\n    specify a range of characters by using a hyphen, but if the hyphen appears\n    as the first or last character enclosed in the square brackets it is taken\n    as a literal hyphen to be included in the character class as a normal\n    character.\n  </p>\n  <p>\n    For example, <code>[abcd]</code> is the same as <code>[a-d]</code>. They\n    match the \"b\" in \"brisket\", and the \"c\" in \"chop\".\n  </p>\n  <p>\n    For example, <code>[abcd-]</code> and <code>[-abcd]</code> match the \"b\" in\n    \"brisket\", the \"c\" in \"chop\", and the \"-\" (hyphen) in \"non-profit\".\n  </p>\n  <p>\n    For example, <code>[\\w-]</code> is the same as <code>[A-Za-z0-9_-]</code>.\n    They both match the \"b\" in \"brisket\", the \"c\" in \"chop\", and the \"n\" in\n    \"non-profit\".\n  </p>\n</td>\n"
```
##### td (51:4) => tableCell
```
type: "paragraph"
summary: "Groups and ranges indicate groups and ranges of expression characters."
rowIndex: 3
shouldWrap: true
children:
  type: "inlineCode"
  value: "[^xyz] [^a-c]"
```
##### td (55:4) => tableCell
```
type: "paragraph"
summary: "Groups and ranges indicate groups and ranges of expression characters."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "A negated or complemented character class. That is, it matches anything that is not enclosed in the brackets. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets it is taken as a literal hyphen to be included in the character class as a normal character. For example, "
  type: "inlineCode"
  value: "[^abc]"
  type: "text"
  value: " is the same as "
  type: "inlineCode"
  value: "[^a-c]"
  type: "text"
  value: ". They initially match \"o\" in \"bacon\" and \"h\" in \"chop\".",type: "blockquote"
children:
  type: "paragraph"
  children:
    type: "strong"
    children:
      type: "text"
      value: "Note:"
    type: "text"
    value: " The ^ character may also indicate the "
    type: "link"
    title:

    url: "/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions"
    children:
      type: "text"
      value: "beginning of input"
    type: "text"
    value: "."
```
##### tr (50:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <code>[^xyz]<br />[^a-c]</code>\n  </p>\n</td>\n",type: "html"
value: "<td>\n  <p>\n    A negated or complemented character class. That is, it matches anything that\n    is not enclosed in the brackets. You can specify a range of characters by\n    using a hyphen, but if the hyphen appears as the first or last character\n    enclosed in the square brackets it is taken as a literal hyphen to be\n    included in the character class as a normal character. For example,\n    <code>[^abc]</code> is the same as <code>[^a-c]</code>. They initially match\n    \"o\" in \"bacon\" and \"h\" in \"chop\".\n  </p>\n  <div class=\"notecard note\">\n    <p>\n      <strong>Note:</strong> The ^ character may also indicate the\n      <a href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions\"\n        >beginning of input</a\n      >.\n    </p>\n  </div>\n</td>\n"
```
##### td (65:4) => tableCell
```
type: "paragraph"
summary: "Groups and ranges indicate groups and ranges of expression characters."
rowIndex: 4
shouldWrap: true
children:
  type: "strong"
  children:
    type: "text"
    value: "Capturing group:"
  type: "text"
  value: " "
  type: "text"
  value: "Matches "
  type: "inlineCode"
  value: "x"
  type: "text"
  value: " and remembers the match. For example, "
  type: "inlineCode"
  value: "/(foo)/"
  type: "text"
  value: " matches and remembers \"foo\" in \"foo bar\". ",type: "paragraph"
summary: "Groups and ranges indicate groups and ranges of expression characters."
rowIndex: 4
shouldWrap: true
children:
  type: "text"
  value: "A regular expression may have multiple capturing groups. In results, matches to capturing groups typically in an array whose members are in the same order as the left parentheses in the capturing group. This is usually just the order of the capturing groups themselves. This becomes important when capturing groups are nested. Matches are accessed using the index of the result's elements ("
  type: "inlineCode"
  value: "[1], ..., [n]"
  type: "text"
  value: ") or from the predefined "
  type: "inlineCode"
  value: "RegExp"
  type: "text"
  value: " object's properties ("
  type: "inlineCode"
  value: "$1, ..., $9"
  type: "text"
  value: ").",type: "paragraph"
summary: "Groups and ranges indicate groups and ranges of expression characters."
rowIndex: 4
shouldWrap: true
children:
  type: "text"
  value: "Capturing groups have a performance penalty. If you don't need the matched substring to be recalled, prefer non-capturing parentheses (see below).",type: "paragraph"
summary: "Groups and ranges indicate groups and ranges of expression characters."
rowIndex: 4
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match"
  children:
    type: "inlineCode"
    value: "String.match()"
  type: "text"
  value: " won't return groups if the "
  type: "inlineCode"
  value: "/.../g"
  type: "text"
  value: " flag is set. However, you can still use "
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/matchAll"
  children:
    type: "inlineCode"
    value: "String.matchAll()"
  type: "text"
  value: " to get all matches."
```
##### tr (63:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <strong>Capturing group: </strong>Matches <code><em>x</em></code> and\n    remembers the match. For example, <code>/(foo)/</code> matches and remembers\n    \"foo\" in \"foo bar\". \n  </p>\n  <p>\n    A regular expression may have multiple capturing groups. In results, matches\n    to capturing groups typically in an array whose members are in the same\n    order as the left parentheses in the capturing group. This is usually just\n    the order of the capturing groups themselves. This becomes important when\n    capturing groups are nested. Matches are accessed using the index of the\n    result's elements (<code>[1], ..., [n]</code>) or from the predefined\n    <code>RegExp</code> object's properties (<code>$1, ..., $9</code>).\n  </p>\n  <p>\n    Capturing groups have a performance penalty. If you don't need the matched\n    substring to be recalled, prefer non-capturing parentheses (see below).\n  </p>\n  <p>\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match\"\n        >String.match()</a\n      ></code\n    >\n    won't return groups if the <code>/.../g</code> flag is set. However, you can\n    still use\n    <code\n      ><a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/matchAll\"\n        >String.matchAll()</a\n      ></code\n    >\n    to get all matches.\n  </p>\n</td>\n"
```
##### td (77:4) => tableCell
```
type: "paragraph"
summary: "Groups and ranges indicate groups and ranges of expression characters."
rowIndex: 5
shouldWrap: true
children:
  type: "text"
  value: "Where \"n\" is a positive integer. A back reference to the last substring matching the n parenthetical in the regular expression (counting left parentheses). For example, "
  type: "inlineCode"
  value: "/apple(,)\\sorange\\1/"
  type: "text"
  value: " matches \"apple, orange,\" in \"apple, orange, cherry, peach\"."
```
##### tr (75:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Where \"n\" is a positive integer. A back reference to the last substring\n    matching the n parenthetical in the regular expression (counting left\n    parentheses). For example, <code>/apple(,)\\sorange\\1/</code> matches \"apple,\n    orange,\" in \"apple, orange, cherry, peach\".\n  </p>\n</td>\n"
```
##### td (83:4) => tableCell
```
type: "paragraph"
summary: "Groups and ranges indicate groups and ranges of expression characters."
rowIndex: 6
shouldWrap: true
children:
  type: "text"
  value: "A back reference to the last substring matching the "
  type: "strong"
  children:
    type: "text"
    value: "Named capture group"
  type: "text"
  value: " specified by "
  type: "inlineCode"
  value: "<Name>"
  type: "text"
  value: ".",type: "paragraph"
summary: "Groups and ranges indicate groups and ranges of expression characters."
rowIndex: 6
shouldWrap: true
children:
  type: "text"
  value: "For example, "
  type: "inlineCode"
  value: "/(?<title>\\w+), yes \\k<title>/"
  type: "text"
  value: " matches \"Sir, yes Sir\" in \"Do you copy? Sir, yes Sir!\".",type: "blockquote"
children:
  type: "paragraph"
  children:
    type: "strong"
    children:
      type: "text"
      value: "Note:"
    type: "text"
    value: " "
    type: "inlineCode"
    value: "\\k"
    type: "text"
    value: " is used literally here to indicate the beginning of a back reference to a Named capture group."
```
##### tr (81:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    A back reference to the last substring matching the\n    <strong>Named capture group</strong> specified by <code>&#x3C;Name></code>.\n  </p>\n  <p>\n    For example, <code>/(?&#x3C;title>\\w+), yes \\k&#x3C;title>/</code> matches\n    \"Sir, yes Sir\" in \"Do you copy? Sir, yes Sir!\".\n  </p>\n  <div class=\"notecard note\">\n    <p>\n      <strong>Note:</strong> <code>\\k</code> is used literally here to indicate\n      the beginning of a back reference to a Named capture group.\n    </p>\n  </div>\n</td>\n"
```
##### td (95:4) => tableCell
```
type: "paragraph"
summary: "Groups and ranges indicate groups and ranges of expression characters."
rowIndex: 7
shouldWrap: true
children:
  type: "strong"
  children:
    type: "text"
    value: "Named capturing group:"
  type: "text"
  value: " "
  type: "text"
  value: "Matches \"x\" and stores it on the groups property of the returned matches under the name specified by "
  type: "inlineCode"
  value: "<Name>"
  type: "text"
  value: ". The angle brackets ("
  type: "inlineCode"
  value: "<"
  type: "text"
  value: " and "
  type: "inlineCode"
  value: ">"
  type: "text"
  value: ") are required for group name.",type: "paragraph"
summary: "Groups and ranges indicate groups and ranges of expression characters."
rowIndex: 7
shouldWrap: true
children:
  type: "text"
  value: "For example, to extract the United States area code from a phone number, we could use "
  type: "inlineCode"
  value: "/\\((?<area>\\d\\d\\d)\\)/"
  type: "text"
  value: ". The resulting number would appear under "
  type: "inlineCode"
  value: "matches.groups.area"
  type: "text"
  value: "."
```
##### tr (93:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <strong>Named capturing group: </strong>Matches \"x\" and stores it on the\n    groups property of the returned matches under the name specified by\n    <code>&#x3C;Name></code>. The angle brackets (<code>&#x3C;</code> and\n    <code>></code>) are required for group name.\n  </p>\n  <p>\n    For example, to extract the United States area code from a phone number, we\n    could use <code>/\\((?&#x3C;area>\\d\\d\\d)\\)/</code>. The resulting number\n    would appear under <code>matches.groups.area</code>.\n  </p>\n</td>\n"
```
##### table.standard-table (23:1) => table
```
type: "html"
value: "<tr>\n  <td>\n    <code><em>x</em>|<em>y</em></code>\n  </td>\n  <td>\n    <p>\n      Matches either \"x\" or \"y\". For example, <code>/green|red/</code> matches\n      \"green\" in \"green apple\" and \"red\" in \"red apple\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code>[xyz]<br />[a-c]</code>\n  </td>\n  <td>\n    <p>\n      A character class. Matches any one of the enclosed characters. You can\n      specify a range of characters by using a hyphen, but if the hyphen appears\n      as the first or last character enclosed in the square brackets it is taken\n      as a literal hyphen to be included in the character class as a normal\n      character.\n    </p>\n    <p>\n      For example, <code>[abcd]</code> is the same as <code>[a-d]</code>. They\n      match the \"b\" in \"brisket\", and the \"c\" in \"chop\".\n    </p>\n    <p>\n      For example, <code>[abcd-]</code> and <code>[-abcd]</code> match the \"b\"\n      in \"brisket\", the \"c\" in \"chop\", and the \"-\" (hyphen) in \"non-profit\".\n    </p>\n    <p>\n      For example, <code>[\\w-]</code> is the same as <code>[A-Za-z0-9_-]</code>.\n      They both match the \"b\" in \"brisket\", the \"c\" in \"chop\", and the \"n\" in\n      \"non-profit\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <p>\n      <code>[^xyz]<br />[^a-c]</code>\n    </p>\n  </td>\n  <td>\n    <p>\n      A negated or complemented character class. That is, it matches anything\n      that is not enclosed in the brackets. You can specify a range of\n      characters by using a hyphen, but if the hyphen appears as the first or\n      last character enclosed in the square brackets it is taken as a literal\n      hyphen to be included in the character class as a normal character. For\n      example, <code>[^abc]</code> is the same as <code>[^a-c]</code>. They\n      initially match \"o\" in \"bacon\" and \"h\" in \"chop\".\n    </p>\n    <div class=\"notecard note\">\n      <p>\n        <strong>Note:</strong> The ^ character may also indicate the\n        <a\n          href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions\"\n          >beginning of input</a\n        >.\n      </p>\n    </div>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>(<em>x</em>)</code></td>\n  <td>\n    <p>\n      <strong>Capturing group: </strong>Matches <code><em>x</em></code> and\n      remembers the match. For example, <code>/(foo)/</code> matches and\n      remembers \"foo\" in \"foo bar\". \n    </p>\n    <p>\n      A regular expression may have multiple capturing groups. In results,\n      matches to capturing groups typically in an array whose members are in the\n      same order as the left parentheses in the capturing group. This is usually\n      just the order of the capturing groups themselves. This becomes important\n      when capturing groups are nested. Matches are accessed using the index of\n      the result's elements (<code>[1], ..., [n]</code>) or from the predefined\n      <code>RegExp</code> object's properties (<code>$1, ..., $9</code>).\n    </p>\n    <p>\n      Capturing groups have a performance penalty. If you don't need the matched\n      substring to be recalled, prefer non-capturing parentheses (see below).\n    </p>\n    <p>\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match\"\n          >String.match()</a\n        ></code\n      >\n      won't return groups if the <code>/.../g</code> flag is set. However, you\n      can still use\n      <code\n        ><a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/matchAll\"\n          >String.matchAll()</a\n        ></code\n      >\n      to get all matches.\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code>\\<em>n</em></code>\n  </td>\n  <td>\n    <p>\n      Where \"n\" is a positive integer. A back reference to the last substring\n      matching the n parenthetical in the regular expression (counting left\n      parentheses). For example, <code>/apple(,)\\sorange\\1/</code> matches\n      \"apple, orange,\" in \"apple, orange, cherry, peach\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>\\k&#x3C;Name></code></td>\n  <td>\n    <p>\n      A back reference to the last substring matching the\n      <strong>Named capture group</strong> specified by\n      <code>&#x3C;Name></code>.\n    </p>\n    <p>\n      For example, <code>/(?&#x3C;title>\\w+), yes \\k&#x3C;title>/</code> matches\n      \"Sir, yes Sir\" in \"Do you copy? Sir, yes Sir!\".\n    </p>\n    <div class=\"notecard note\">\n      <p>\n        <strong>Note:</strong> <code>\\k</code> is used literally here to\n        indicate the beginning of a back reference to a Named capture group.\n      </p>\n    </div>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>(?&#x3C;Name>x)</code></td>\n  <td>\n    <p>\n      <strong>Named capturing group: </strong>Matches \"x\" and stores it on the\n      groups property of the returned matches under the name specified by\n      <code>&#x3C;Name></code>. The angle brackets (<code>&#x3C;</code> and\n      <code>></code>) are required for group name.\n    </p>\n    <p>\n      For example, to extract the United States area code from a phone number,\n      we could use <code>/\\((?&#x3C;area>\\d\\d\\d)\\)/</code>. The resulting number\n      would appear under <code>matches.groups.area</code>.\n    </p>\n  </td>\n</tr>\n"
```
### [/en-US/docs/Web/JavaScript/Guide/Regular_Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)
#### Invalid AST transformations
##### td (85:4) => tableCell
```
type: "paragraph"
summary: "Regular expressions are patterns used to match character combinations in strings. In JavaScript, regular expressions are also objects. These patterns are used with the {{anN4cmVmKCJSZWdFeHAuZXhlYyIsICJleGVjKCkiKQ==}} and {{anN4cmVmKCJSZWdFeHAudGVzdCIsICJ0ZXN0KCkiKQ==}} methods of {{anN4cmVmKCJSZWdFeHAiKQ==}}, and with the {{anN4cmVmKCJTdHJpbmcubWF0Y2giLCAibWF0Y2goKSIp}}, {{anN4cmVmKCJTdHJpbmcubWF0Y2hBbGwiLCAibWF0Y2hBbGwoKSIp}}, {{anN4cmVmKCJTdHJpbmcucmVwbGFjZSIsICJyZXBsYWNlKCkiKQ==}}, {{anN4cmVmKCJTdHJpbmcucmVwbGFjZUFsbCIsICJyZXBsYWNlQWxsKCkiKQ==}}, {{anN4cmVmKCJTdHJpbmcuc2VhcmNoIiwgInNlYXJjaCgpIik=}}, and {{anN4cmVmKCJTdHJpbmcuc3BsaXQiLCAic3BsaXQoKSIp}} methods of {{anN4cmVmKCJTdHJpbmciKQ==}}. This chapter describes JavaScript regular expressions."
rowIndex: 1
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes"
  children:
    type: "text"
    value: "Character classes"
```
##### tr (83:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <a\n      href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes\"\n      >Character classes</a\n    >\n  </p>\n</td>\n"
```
##### td (91:4) => tableCell
```
type: "paragraph"
summary: "Regular expressions are patterns used to match character combinations in strings. In JavaScript, regular expressions are also objects. These patterns are used with the {{anN4cmVmKCJSZWdFeHAuZXhlYyIsICJleGVjKCkiKQ==}} and {{anN4cmVmKCJSZWdFeHAudGVzdCIsICJ0ZXN0KCkiKQ==}} methods of {{anN4cmVmKCJSZWdFeHAiKQ==}}, and with the {{anN4cmVmKCJTdHJpbmcubWF0Y2giLCAibWF0Y2goKSIp}}, {{anN4cmVmKCJTdHJpbmcubWF0Y2hBbGwiLCAibWF0Y2hBbGwoKSIp}}, {{anN4cmVmKCJTdHJpbmcucmVwbGFjZSIsICJyZXBsYWNlKCkiKQ==}}, {{anN4cmVmKCJTdHJpbmcucmVwbGFjZUFsbCIsICJyZXBsYWNlQWxsKCkiKQ==}}, {{anN4cmVmKCJTdHJpbmcuc2VhcmNoIiwgInNlYXJjaCgpIik=}}, and {{anN4cmVmKCJTdHJpbmcuc3BsaXQiLCAic3BsaXQoKSIp}} methods of {{anN4cmVmKCJTdHJpbmciKQ==}}. This chapter describes JavaScript regular expressions."
rowIndex: 2
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions"
  children:
    type: "text"
    value: "Assertions"
```
##### tr (89:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <a href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions\"\n      >Assertions</a\n    >\n  </p>\n</td>\n"
```
##### td (97:4) => tableCell
```
type: "paragraph"
summary: "Regular expressions are patterns used to match character combinations in strings. In JavaScript, regular expressions are also objects. These patterns are used with the {{anN4cmVmKCJSZWdFeHAuZXhlYyIsICJleGVjKCkiKQ==}} and {{anN4cmVmKCJSZWdFeHAudGVzdCIsICJ0ZXN0KCkiKQ==}} methods of {{anN4cmVmKCJSZWdFeHAiKQ==}}, and with the {{anN4cmVmKCJTdHJpbmcubWF0Y2giLCAibWF0Y2goKSIp}}, {{anN4cmVmKCJTdHJpbmcubWF0Y2hBbGwiLCAibWF0Y2hBbGwoKSIp}}, {{anN4cmVmKCJTdHJpbmcucmVwbGFjZSIsICJyZXBsYWNlKCkiKQ==}}, {{anN4cmVmKCJTdHJpbmcucmVwbGFjZUFsbCIsICJyZXBsYWNlQWxsKCkiKQ==}}, {{anN4cmVmKCJTdHJpbmcuc2VhcmNoIiwgInNlYXJjaCgpIik=}}, and {{anN4cmVmKCJTdHJpbmcuc3BsaXQiLCAic3BsaXQoKSIp}} methods of {{anN4cmVmKCJTdHJpbmciKQ==}}. This chapter describes JavaScript regular expressions."
rowIndex: 3
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges"
  children:
    type: "text"
    value: "Groups and ranges"
```
##### tr (95:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <a\n      href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges\"\n      >Groups and ranges</a\n    >\n  </p>\n</td>\n"
```
##### td (103:4) => tableCell
```
type: "paragraph"
summary: "Regular expressions are patterns used to match character combinations in strings. In JavaScript, regular expressions are also objects. These patterns are used with the {{anN4cmVmKCJSZWdFeHAuZXhlYyIsICJleGVjKCkiKQ==}} and {{anN4cmVmKCJSZWdFeHAudGVzdCIsICJ0ZXN0KCkiKQ==}} methods of {{anN4cmVmKCJSZWdFeHAiKQ==}}, and with the {{anN4cmVmKCJTdHJpbmcubWF0Y2giLCAibWF0Y2goKSIp}}, {{anN4cmVmKCJTdHJpbmcubWF0Y2hBbGwiLCAibWF0Y2hBbGwoKSIp}}, {{anN4cmVmKCJTdHJpbmcucmVwbGFjZSIsICJyZXBsYWNlKCkiKQ==}}, {{anN4cmVmKCJTdHJpbmcucmVwbGFjZUFsbCIsICJyZXBsYWNlQWxsKCkiKQ==}}, {{anN4cmVmKCJTdHJpbmcuc2VhcmNoIiwgInNlYXJjaCgpIik=}}, and {{anN4cmVmKCJTdHJpbmcuc3BsaXQiLCAic3BsaXQoKSIp}} methods of {{anN4cmVmKCJTdHJpbmciKQ==}}. This chapter describes JavaScript regular expressions."
rowIndex: 4
shouldWrap: true
children:
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Quantifiers"
  children:
    type: "text"
    value: "Quantifiers"
```
##### tr (101:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <a href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Quantifiers\"\n      >Quantifiers</a\n    >\n  </p>\n</td>\n"
```
##### table.standard-table (74:1) => table
```
type: "html"
value: "<tr>\n  <td>\n    <code>\\</code>, <code>.</code>, <code>\\cX</code>, <code>\\d</code>,\n    <code>\\D</code>, <code>\\f</code>, <code>\\n</code>, <code>\\r</code>,\n    <code>\\s</code>, <code>\\S</code>, <code>\\t</code>, <code>\\v</code>,\n    <code>\\w</code>, <code>\\W</code>, <code>\\0</code>, <code>\\xhh</code>,\n    <code>\\uhhhh</code>, <code>\\uhhhhh</code>, <code>[\\b]</code>\n  </td>\n  <td>\n    <p>\n      <a\n        href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes\"\n        >Character classes</a\n      >\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code>^</code>, <code>$</code>, <code>x(?=y)</code>, <code>x(?!y)</code>,\n    <code>(?&#x3C;=y)x</code>, <code>(?&#x3C;!y)x</code>, <code>\\b</code>,\n    <code>\\B</code>\n  </td>\n  <td>\n    <p>\n      <a href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Assertions\"\n        >Assertions</a\n      >\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code>(x)</code>, <code>(?:x)</code>, <code>(?&#x3C;Name>x)</code>,\n    <code>x|y</code>, <code>[xyz]</code>, <code>[^xyz]</code>,\n    <code>\\<em>Number</em></code>\n  </td>\n  <td>\n    <p>\n      <a\n        href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Ranges\"\n        >Groups and ranges</a\n      >\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code>*</code>, <code>+</code>, <code>?</code>, <code>x{<em>n</em>}</code>,\n    <code>x{<em>n</em>,}</code>, <code>x{<em>n</em>,<em>m</em>}</code>\n  </td>\n  <td>\n    <p>\n      <a href=\"/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Quantifiers\"\n        >Quantifiers</a\n      >\n    </p>\n  </td>\n</tr>\n"
```
##### tr (228:3) => tableRow
```
type: "html"
value: "<td rowspan=\"4\"><code>myArray</code></td>\n"
```
##### tr (249:3) => tableRow
```
type: "html"
value: "<td rowspan=\"2\"><code>myRe</code></td>\n"
```
##### table.standard-table (217:1) => table
```
type: "html"
value: "<tr>\n  <td rowspan=\"4\"><code>myArray</code></td>\n  <td></td>\n  <td>The matched string and all remembered substrings.</td>\n  <td><code>['dbbd', 'bb', index: 1, input: 'cdbbdbsbz']</code></td>\n</tr>\n",type: "html"
value: "<tr>\n  <td rowspan=\"2\"><code>myRe</code></td>\n  <td><code>lastIndex</code></td>\n  <td>\n    The index at which to start the next match. (This property is set only if\n    the regular expression uses the g option, described in\n    <a href=\"#advanced_searching_with_flags\">Advanced Searching With Flags</a>.)\n  </td>\n  <td><code>5</code></td>\n</tr>\n"
```
### Missing conversion rules
- td[rowSpan="4"] (229:4)
- td[rowSpan="2"] (250:4)
- kbd (405:65)
### [/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Quantifiers](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Quantifiers)
#### Invalid AST transformations
##### td (36:4) => tableCell
```
type: "paragraph"
summary: "Quantifiers indicate numbers of characters or expressions to match."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "Matches the preceding item \"x\" 0 or more times. For example, "
  type: "inlineCode"
  value: "/bo*/"
  type: "text"
  value: " matches \"boooo\" in \"A ghost booooed\" and \"b\" in \"A bird warbled\", but nothing in \"A goat grunted\"."
```
##### tr (34:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches the preceding item \"x\" 0 or more times. For example,\n    <code>/bo*/</code> matches \"boooo\" in \"A ghost booooed\" and \"b\" in \"A bird\n    warbled\", but nothing in \"A goat grunted\".\n  </p>\n</td>\n"
```
##### td (42:4) => tableCell
```
type: "paragraph"
summary: "Quantifiers indicate numbers of characters or expressions to match."
rowIndex: 2
shouldWrap: true
children:
  type: "text"
  value: "Matches the preceding item \"x\" 1 or more times. Equivalent to "
  type: "inlineCode"
  value: "{1,}"
  type: "text"
  value: ". For example, "
  type: "inlineCode"
  value: "/a+/"
  type: "text"
  value: " matches the \"a\" in \"candy\" and all the \"a\"'s in \"caaaaaaandy\"."
```
##### tr (40:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches the preceding item \"x\" 1 or more times. Equivalent to\n    <code>{1,}</code>. For example, <code>/a+/</code> matches the \"a\" in \"candy\"\n    and all the \"a\"'s in \"caaaaaaandy\".\n  </p>\n</td>\n"
```
##### td (48:4) => tableCell
```
type: "paragraph"
summary: "Quantifiers indicate numbers of characters or expressions to match."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "Matches the preceding item \"x\" 0 or 1 times. For example, "
  type: "inlineCode"
  value: "/e?le?/"
  type: "text"
  value: " matches the \"el\" in \"angel\" and the \"le\" in \"angle.\"",type: "paragraph"
summary: "Quantifiers indicate numbers of characters or expressions to match."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "If used immediately after any of the quantifiers "
  type: "inlineCode"
  value: "*"
  type: "text"
  value: ", "
  type: "inlineCode"
  value: "+"
  type: "text"
  value: ", "
  type: "inlineCode"
  value: "?"
  type: "text"
  value: ", or "
  type: "inlineCode"
  value: "{}"
  type: "text"
  value: ", makes the quantifier non-greedy (matching the minimum number of times), as opposed to the default, which is greedy (matching the maximum number of times)."
```
##### tr (46:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Matches the preceding item \"x\" 0 or 1 times. For example,\n    <code>/e?le?/</code> matches the \"el\" in \"angel\" and the \"le\" in \"angle.\"\n  </p>\n  <p>\n    If used immediately after any of the quantifiers <code>*</code>,\n    <code>+</code>, <code>?</code>, or <code>{}</code>, makes the quantifier\n    non-greedy (matching the minimum number of times), as opposed to the\n    default, which is greedy (matching the maximum number of times).\n  </p>\n</td>\n"
```
##### td (56:4) => tableCell
```
type: "paragraph"
summary: "Quantifiers indicate numbers of characters or expressions to match."
rowIndex: 4
shouldWrap: true
children:
  type: "text"
  value: "Where \"n\" is a positive integer, matches exactly \"n\" occurrences of the preceding item \"x\". For example, "
  type: "inlineCode"
  value: "/a{2}/"
  type: "text"
  value: " doesn't match the \"a\" in \"candy\", but it matches all of the \"a\"'s in \"caandy\", and the first two \"a\"'s in \"caaandy\"."
```
##### tr (54:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Where \"n\" is a positive integer, matches exactly \"n\" occurrences of the\n    preceding item \"x\". For example, <code>/a{2}/</code> doesn't match the \"a\"\n    in \"candy\", but it matches all of the \"a\"'s in \"caandy\", and the first two\n    \"a\"'s in \"caaandy\".\n  </p>\n</td>\n"
```
##### td (62:4) => tableCell
```
type: "paragraph"
summary: "Quantifiers indicate numbers of characters or expressions to match."
rowIndex: 5
shouldWrap: true
children:
  type: "text"
  value: "Where \"n\" is a positive integer, matches at least \"n\" occurrences of the preceding item \"x\". For example, "
  type: "inlineCode"
  value: "/a{2,}/"
  type: "text"
  value: " doesn't match the \"a\" in \"candy\", but matches all of the a's in \"caandy\" and in \"caaaaaaandy\"."
```
##### tr (60:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Where \"n\" is a positive integer, matches at least \"n\" occurrences of the\n    preceding item \"x\". For example, <code>/a{2,}/</code> doesn't match the \"a\"\n    in \"candy\", but matches all of the a's in \"caandy\" and in \"caaaaaaandy\".\n  </p>\n</td>\n"
```
##### td (68:4) => tableCell
```
type: "paragraph"
summary: "Quantifiers indicate numbers of characters or expressions to match."
rowIndex: 6
shouldWrap: true
children:
  type: "text"
  value: "Where \"n\" is 0 or a positive integer, \"m\" is a positive integer, and "
  type: "inlineCode"
  value: "m > n"
  type: "text"
  value: ", matches at least \"n\" and at most \"m\" occurrences of the preceding item \"x\". For example, "
  type: "inlineCode"
  value: "/a{1,3}/"
  type: "text"
  value: " matches nothing in \"cndy\", the \"a\" in \"candy\", the two \"a\"'s in \"caandy\", and the first three \"a\"'s in \"caaaaaaandy\". Notice that when matching \"caaaaaaandy\", the match is \"aaa\", even though the original string had more \"a\"s in it."
```
##### tr (66:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Where \"n\" is 0 or a positive integer, \"m\" is a positive integer, and\n    <code><em>m</em> > <em>n</em></code\n    >, matches at least \"n\" and at most \"m\" occurrences of the preceding item\n    \"x\". For example, <code>/a{1,3}/</code> matches nothing in \"cndy\", the \"a\"\n    in \"candy\", the two \"a\"'s in \"caandy\", and the first three \"a\"'s in\n    \"caaaaaaandy\". Notice that when matching \"caaaaaaandy\", the match is \"aaa\",\n    even though the original string had more \"a\"s in it.\n  </p>\n</td>\n"
```
##### td (73:4) => tableCell
```
type: "paragraph"
summary: "Quantifiers indicate numbers of characters or expressions to match."
rowIndex: 7
shouldWrap: true
children:
  type: "inlineCode"
  value: "x*?"
  type: "break"
  type: "inlineCode"
  value: "x+?"
  type: "break"
  type: "inlineCode"
  value: "x??"
  type: "break"
  type: "inlineCode"
  value: "x{n}?"
  type: "break"
  type: "inlineCode"
  value: "x{n,}?"
  type: "break"
  type: "inlineCode"
  value: "x{n,m}?"
```
##### td (81:4) => tableCell
```
type: "paragraph"
summary: "Quantifiers indicate numbers of characters or expressions to match."
rowIndex: 7
shouldWrap: true
children:
  type: "text"
  value: "By default quantifiers like "
  type: "inlineCode"
  value: "*"
  type: "text"
  value: " and "
  type: "inlineCode"
  value: "+"
  type: "text"
  value: " are \"greedy\", meaning that they try to match as much of the string as possible. The "
  type: "inlineCode"
  value: "?"
  type: "text"
  value: " character after the quantifier makes the quantifier \"non-greedy\": meaning that it will stop as soon as it finds a match. For example, given a string like \"some <foo> <bar> new </bar> </foo> thing\":",type: "list"
ordered: false
start:

spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "inlineCode"
      value: "/<.*>/"
      type: "text"
      value: " will match \"<foo> <bar> new </bar> </foo>\""
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "inlineCode"
      value: "/<.*?>/"
      type: "text"
      value: " will match \"<foo>\""
```
##### tr (72:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <code><em>x</em>*?</code><br /><code><em>x</em>+?</code><br /><code\n      ><em>x</em>??</code\n    ><br /><code><em>x</em>{n}?</code><br /><code><em>x</em>{n,}?</code\n    ><br /><code><em>x</em>{n,m}?</code>\n  </p>\n</td>\n",type: "html"
value: "<td>\n  <p>\n    By default quantifiers like <code>*</code> and <code>+</code> are \"greedy\",\n    meaning that they try to match as much of the string as possible. The\n    <code>?</code> character after the quantifier makes the quantifier\n    \"non-greedy\": meaning that it will stop as soon as it finds a match. For\n    example, given a string like \"some &#x3C;foo> &#x3C;bar> new &#x3C;/bar>\n    &#x3C;/foo> thing\":\n  </p>\n  <ul>\n    <li>\n      <code>/&#x3C;.*>/</code> will match \"&#x3C;foo> &#x3C;bar> new &#x3C;/bar>\n      &#x3C;/foo>\"\n    </li>\n    <li><code>/&#x3C;.*?>/</code> will match \"&#x3C;foo>\"</li>\n  </ul>\n</td>\n"
```
##### table.standard-table (26:1) => table
```
type: "html"
value: "<tr>\n  <td>\n    <code><em>x</em>*</code>\n  </td>\n  <td>\n    <p>\n      Matches the preceding item \"x\" 0 or more times. For example,\n      <code>/bo*/</code> matches \"boooo\" in \"A ghost booooed\" and \"b\" in \"A bird\n      warbled\", but nothing in \"A goat grunted\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code><em>x</em>+</code>\n  </td>\n  <td>\n    <p>\n      Matches the preceding item \"x\" 1 or more times. Equivalent to\n      <code>{1,}</code>. For example, <code>/a+/</code> matches the \"a\" in\n      \"candy\" and all the \"a\"'s in \"caaaaaaandy\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code><em>x</em>?</code>\n  </td>\n  <td>\n    <p>\n      Matches the preceding item \"x\" 0 or 1 times. For example,\n      <code>/e?le?/</code> matches the \"el\" in \"angel\" and the \"le\" in \"angle.\"\n    </p>\n    <p>\n      If used immediately after any of the quantifiers <code>*</code>,\n      <code>+</code>, <code>?</code>, or <code>{}</code>, makes the quantifier\n      non-greedy (matching the minimum number of times), as opposed to the\n      default, which is greedy (matching the maximum number of times).\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code><em>x</em>{<em>n</em>}</code>\n  </td>\n  <td>\n    <p>\n      Where \"n\" is a positive integer, matches exactly \"n\" occurrences of the\n      preceding item \"x\". For example, <code>/a{2}/</code> doesn't match the \"a\"\n      in \"candy\", but it matches all of the \"a\"'s in \"caandy\", and the first two\n      \"a\"'s in \"caaandy\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code><em>x</em>{<em>n</em>,}</code>\n  </td>\n  <td>\n    <p>\n      Where \"n\" is a positive integer, matches at least \"n\" occurrences of the\n      preceding item \"x\". For example, <code>/a{2,}/</code> doesn't match the\n      \"a\" in \"candy\", but matches all of the a's in \"caandy\" and in\n      \"caaaaaaandy\".\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <code><em>x</em>{<em>n</em>,<em>m</em>}</code>\n  </td>\n  <td>\n    <p>\n      Where \"n\" is 0 or a positive integer, \"m\" is a positive integer, and\n      <code><em>m</em> > <em>n</em></code\n      >, matches at least \"n\" and at most \"m\" occurrences of the preceding item\n      \"x\". For example, <code>/a{1,3}/</code> matches nothing in \"cndy\", the \"a\"\n      in \"candy\", the two \"a\"'s in \"caandy\", and the first three \"a\"'s in\n      \"caaaaaaandy\". Notice that when matching \"caaaaaaandy\", the match is\n      \"aaa\", even though the original string had more \"a\"s in it.\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <p>\n      <code><em>x</em>*?</code><br /><code><em>x</em>+?</code><br /><code\n        ><em>x</em>??</code\n      ><br /><code><em>x</em>{n}?</code><br /><code><em>x</em>{n,}?</code\n      ><br /><code><em>x</em>{n,m}?</code>\n    </p>\n  </td>\n  <td>\n    <p>\n      By default quantifiers like <code>*</code> and <code>+</code> are\n      \"greedy\", meaning that they try to match as much of the string as\n      possible. The <code>?</code> character after the quantifier makes the\n      quantifier \"non-greedy\": meaning that it will stop as soon as it finds a\n      match. For example, given a string like \"some &#x3C;foo> &#x3C;bar> new\n      &#x3C;/bar> &#x3C;/foo> thing\":\n    </p>\n    <ul>\n      <li>\n        <code>/&#x3C;.*>/</code> will match \"&#x3C;foo> &#x3C;bar> new\n        &#x3C;/bar> &#x3C;/foo>\"\n      </li>\n      <li><code>/&#x3C;.*?>/</code> will match \"&#x3C;foo>\"</li>\n    </ul>\n  </td>\n</tr>\n"
```
### [/en-US/docs/Web/JavaScript/Guide/Text_formatting](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Text_formatting)
#### Invalid AST transformations
##### td (133:4) => tableCell
```
type: "paragraph"
summary: "This chapter introduces how to work with strings and text in JavaScript."
rowIndex: 10
shouldWrap: true
children:
  type: "text"
  value: "Return the string in all lowercase or all uppercase, respectively."
```
##### tr (131:3) => tableRow
```
type: "html"
value: "<td>\n  <p>Return the string in all lowercase or all uppercase, respectively.</p>\n</td>\n"
```
##### table.standard-table (84:1) => table
```
type: "html"
value: "<tr>\n  <td>\n    {{anN4cmVmKCJTdHJpbmcudG9Mb3dlckNhc2UiLCAidG9Mb3dlckNhc2UiKQ==}},\n    {{anN4cmVmKCJTdHJpbmcudG9VcHBlckNhc2UiLCAidG9VcHBlckNhc2UiKQ==}}\n  </td>\n  <td>\n    <p>Return the string in all lowercase or all uppercase, respectively.</p>\n  </td>\n</tr>\n"
```
### [/en-US/docs/Web/JavaScript/Guide/Using_promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises)
### Missing conversion rules
- p.summary (16:1)
### [/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)
#### Invalid AST transformations
##### tr (406:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">Pro(s)</th>\n",type: "html"
value: "<td>\n  Supported in all browsers — including older browsers (going all the way back\n  to IE 5.5). Also, it is very fast, very standard, and very JIT-optimizable.\n</td>\n"
```
##### td (412:7) => tableCell
```
type: "paragraph"
summary: "JavaScript is a bit confusing for developers experienced in class-based languages (like Java or C++), as it is dynamic and does not provide a class implementation per se (the class keyword is introduced in ES2015, but is syntactical sugar, JavaScript remains prototype-based)."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "Both of those are generally not problems in practice."
```
##### tr (410:7) => tableRow
```
type: "html"
value: "<th scope=\"row\">Con(s)</th>\n",type: "html"
value: "<td>\n  <div>\n    1. In order to use this method, the function in question must be\n    initialized. During this initialization, the constructor may store unique\n    information that must be generated per-object. This unique information would\n    only be generated once, potentially leading to problems.\n  </div>\n  <div>\n    2. The initialization of the constructor may put unwanted methods onto the\n    object.\n  </div>\n  <p>Both of those are generally not problems in practice.</p>\n</td>\n"
```
##### table.standard-table (403:1) => table
```
type: "html"
value: "<tr>\n  <th scope=\"row\">Pro(s)</th>\n  <td>\n    Supported in all browsers — including older browsers (going all the way back\n    to IE 5.5). Also, it is very fast, very standard, and very JIT-optimizable.\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Con(s)</th>\n  <td>\n    <div>\n      1. In order to use this method, the function in question must be\n      initialized. During this initialization, the constructor may store unique\n      information that must be generated per-object. This unique information\n      would only be generated once, potentially leading to problems.\n    </div>\n    <div>\n      2. The initialization of the constructor may put unwanted methods onto the\n      object.\n    </div>\n    <p>Both of those are generally not problems in practice.</p>\n  </td>\n</tr>\n"
```
##### tr (458:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">Pro(s)</th>\n",type: "html"
value: "<td>\n  Supported in all modern browsers. Allows the direct setting of\n  <code>__proto__</code> in a way that is a single event, which permits the\n  browser to further optimize the object. Also allows the creation of objects\n  without a prototype, using <code>Object.create(null)</code>.\n</td>\n"
```
##### tr (462:7) => tableRow
```
type: "html"
value: "<th scope=\"row\">Con(s)</th>\n"
```
##### table.standard-table (455:1) => table
```
type: "html"
value: "<tr>\n  <th scope=\"row\">Pro(s)</th>\n  <td>\n    Supported in all modern browsers. Allows the direct setting of\n    <code>__proto__</code> in a way that is a single event, which permits the\n    browser to further optimize the object. Also allows the creation of objects\n    without a prototype, using <code>Object.create(null)</code>.\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Con(s)</th>\n  <td>\n    Not supported in IE8 and below. However, as Microsoft has discontinued\n    extended support for systems running IE8 and below, that should not be a\n    concern for most applications. Additionally, the slow object initialization\n    can be a performance black hole if using the second argument, because each\n    object-descriptor property has its own separate descriptor object. When\n    dealing with hundreds of thousands of object descriptors in the form of\n    objects, that lag time might become a serious issue.\n  </td>\n</tr>\n"
```
##### tr (506:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">Pro(s)</th>\n",type: "html"
value: "<td>\n  Supported in all modern browsers. Allows the dynamic manipulation of an\n  object’s prototype and can even force a prototype on a prototype-less object\n  created with <code>Object.create(null)</code>.\n</td>\n"
```
##### tr (510:7) => tableRow
```
type: "html"
value: "<th scope=\"row\">Con(s)</th>\n"
```
##### table.standard-table (503:1) => table
```
type: "html"
value: "<tr>\n  <th scope=\"row\">Pro(s)</th>\n  <td>\n    Supported in all modern browsers. Allows the dynamic manipulation of an\n    object’s prototype and can even force a prototype on a prototype-less object\n    created with <code>Object.create(null)</code>.\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Con(s)</th>\n  <td>\n    Ill-performing. Should be deprecated. Many browsers optimize the prototype\n    and try to guess the location of the method in memory when calling an\n    instance in advance; but setting the prototype dynamically disrupts all\n    those optimizations. It might cause some browsers to recompile your code for\n    de-optimization, to make it work according to the specs. Not supported in\n    IE8 and below.\n  </td>\n</tr>\n"
```
##### tr (549:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">Pro(s)</th>\n",type: "html"
value: "<td>\n  Supported in all modern browsers. Setting\n  {{anN4cmVmKCJPYmplY3QvcHJvdG8iLCJfX3Byb3RvX18iKQ==}} to something that is not\n  an object only fails silently. It does not throw an exception.\n</td>\n"
```
##### tr (554:7) => tableRow
```
type: "html"
value: "<th scope=\"row\">Con(s)</th>\n"
```
##### table.standard-table (546:4) => table
```
type: "html"
value: "<tr>\n  <th scope=\"row\">Pro(s)</th>\n  <td>\n    Supported in all modern browsers. Setting\n    {{anN4cmVmKCJPYmplY3QvcHJvdG8iLCJfX3Byb3RvX18iKQ==}} to something that is\n    not an object only fails silently. It does not throw an exception.\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Con(s)</th>\n  <td>\n    Non-performant and deprecated. Many browsers optimize the prototype and try\n    to guess the location of the method in the memory when calling an instance\n    in advance; but setting the prototype dynamically disrupts all those\n    optimizations and can even force some browsers to recompile for\n    de-optimization of your code, to make it work according to the specs. Not\n    supported in IE10 and below.\n  </td>\n</tr>\n"
```
### Missing conversion rules
- th[scope="row"] (407:7)
- td (408:7)
- th[scope="row"] (411:7)
- th[scope="row"] (459:7)
- td (460:7)
- th[scope="row"] (463:7)
- th[scope="row"] (507:7)
- td (508:7)
- th[scope="row"] (511:7)
- th[scope="row"] (550:7)
- td (551:7)
- th[scope="row"] (555:7)
### [/en-US/docs/Web/JavaScript/Language_Resources](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Language_Resources)
#### Invalid AST transformations
##### tr (23:3) => tableRow
```
type: "html"
value: "<th colspan=\"4\">Current editions</th>\n"
```
##### td (28:4) => tableCell
```
type: "paragraph"
summary: "ECMAScript is the scripting language that forms the basis of JavaScript. ECMAScript standardized by the ECMA International standards organization in the ECMA-262 and ECMA-402 specifications. The following ECMAScript standards have been approved or are being worked on:"
rowIndex: 2
shouldWrap: true
children:
  type: "link"
  title:

  url: "https://www.ecma-international.org/publications/files/ECMA-ST/ECMA-262.pdf"
  children:
    type: "text"
    value: "PDF"
  type: "text"
  value: ", "
  type: "link"
  title:

  url: "https://ecma-international.org/ecma-262/11.0/index.html"
  children:
    type: "text"
    value: "HTML"
  type: "text"
  value: ", "
  type: "link"
  title:

  url: "https://tc39.github.io/ecma262/"
  children:
    type: "text"
    value: "Working draft"
  type: "text"
  value: ", "
  type: "link"
  title:

  url: "https://github.com/tc39/ecma262"
  children:
    type: "text"
    value: "repository"
```
##### tr (26:4) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <a\n      href=\"https://www.ecma-international.org/publications/files/ECMA-ST/ECMA-262.pdf\"\n      >PDF</a\n    >,\n    <a href=\"https://ecma-international.org/ecma-262/11.0/index.html\">HTML</a>,\n    <a href=\"https://tc39.github.io/ecma262/\">Working draft</a>,\n    <a href=\"https://github.com/tc39/ecma262\">repository</a>\n  </p>\n</td>\n"
```
##### td (36:4) => tableCell
```
type: "paragraph"
summary: "ECMAScript is the scripting language that forms the basis of JavaScript. ECMAScript standardized by the ECMA International standards organization in the ECMA-262 and ECMA-402 specifications. The following ECMAScript standards have been approved or are being worked on:"
rowIndex: 3
shouldWrap: true
children:
  type: "link"
  title:

  url: "https://www.ecma-international.org/publications/files/ECMA-ST/ECMA-262.pdf"
  children:
    type: "text"
    value: "PDF"
  type: "text"
  value: ", "
  type: "link"
  title:

  url: "https://ecma-international.org/ecma-262/10.0/index.html"
  children:
    type: "text"
    value: "HTML"
  type: "text"
  value: ", "
  type: "link"
  title:

  url: "https://tc39.github.io/ecma262/"
  children:
    type: "text"
    value: "Working draft"
  type: "text"
  value: ", "
  type: "link"
  title:

  url: "https://github.com/tc39/ecma262"
  children:
    type: "text"
    value: "repository"
```
##### tr (34:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <a\n      href=\"https://www.ecma-international.org/publications/files/ECMA-ST/ECMA-262.pdf\"\n      >PDF</a\n    >,\n    <a href=\"https://ecma-international.org/ecma-262/10.0/index.html\">HTML</a\n    >, <a href=\"https://tc39.github.io/ecma262/\">Working draft</a>,\n    <a href=\"https://github.com/tc39/ecma262\">repository</a>\n  </p>\n</td>\n"
```
##### td (44:4) => tableCell
```
type: "paragraph"
summary: "ECMAScript is the scripting language that forms the basis of JavaScript. ECMAScript standardized by the ECMA International standards organization in the ECMA-262 and ECMA-402 specifications. The following ECMAScript standards have been approved or are being worked on:"
rowIndex: 4
shouldWrap: true
children:
  type: "link"
  title:

  url: "http://ecma-international.org/publications/files/ECMA-ST/Ecma-262.pdf"
  children:
    type: "text"
    value: "PDF"
  type: "text"
  value: ", "
  type: "link"
  title:

  url: "http://ecma-international.org/ecma-262/9.0/index.html#Title"
  children:
    type: "text"
    value: "HTML"
  type: "text"
  value: ", "
  type: "break"
  type: "link"
  title:

  url: "https://tc39.github.io/ecma262/"
  children:
    type: "text"
    value: "Working draft"
  type: "text"
  value: ", "
  type: "link"
  title:

  url: "https://github.com/tc39/ecma262"
  children:
    type: "text"
    value: "repository"
```
##### tr (42:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    <a\n      href=\"http://ecma-international.org/publications/files/ECMA-ST/Ecma-262.pdf\"\n      >PDF</a\n    >,\n    <a href=\"http://ecma-international.org/ecma-262/9.0/index.html#Title\"\n      >HTML</a\n    >, <br /><a href=\"https://tc39.github.io/ecma262/\">Working draft</a>,\n    <a href=\"https://github.com/tc39/ecma262\">repository</a>\n  </p>\n</td>\n"
```
##### tr (57:3) => tableRow
```
type: "html"
value: "<th colspan=\"4\">Obsolete/historical editions</th>\n"
```
##### table.standard-table (15:1) => table
```
type: "html"
value: "<tr>\n  <th colspan=\"4\">Current editions</th>\n</tr>\n",type: "html"
value: "<tr>\n  <td>ECMA-262 11th Edition</td>\n  <td>\n    <p>\n      <a\n        href=\"https://www.ecma-international.org/publications/files/ECMA-ST/ECMA-262.pdf\"\n        >PDF</a\n      >,\n      <a href=\"https://ecma-international.org/ecma-262/11.0/index.html\">HTML</a\n      >, <a href=\"https://tc39.github.io/ecma262/\">Working draft</a>,\n      <a href=\"https://github.com/tc39/ecma262\">repository</a>\n    </p>\n  </td>\n  <td>2020</td>\n  <td>ECMAScript 2020 Language Specification</td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>ECMA-262 10th Edition</td>\n  <td>\n    <p>\n      <a\n        href=\"https://www.ecma-international.org/publications/files/ECMA-ST/ECMA-262.pdf\"\n        >PDF</a\n      >,\n      <a href=\"https://ecma-international.org/ecma-262/10.0/index.html\">HTML</a\n      >, <a href=\"https://tc39.github.io/ecma262/\">Working draft</a>,\n      <a href=\"https://github.com/tc39/ecma262\">repository</a>\n    </p>\n  </td>\n  <td>2019</td>\n  <td>ECMAScript 2019 Language Specification</td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>ECMA-262 9th Edition</td>\n  <td>\n    <p>\n      <a\n        href=\"http://ecma-international.org/publications/files/ECMA-ST/Ecma-262.pdf\"\n        >PDF</a\n      >,\n      <a href=\"http://ecma-international.org/ecma-262/9.0/index.html#Title\"\n        >HTML</a\n      >, <br /><a href=\"https://tc39.github.io/ecma262/\">Working draft</a>,\n      <a href=\"https://github.com/tc39/ecma262\">repository</a>\n    </p>\n  </td>\n  <td>2018</td>\n  <td>ECMAScript 2018 Language Specification</td>\n</tr>\n",type: "html"
value: "<tr>\n  <th colspan=\"4\">Obsolete/historical editions</th>\n</tr>\n"
```
### Missing conversion rules
- th[colSpan="4"] (24:4)
- th[colSpan="4"] (58:4)
### [/en-US/docs/Web/JavaScript/Reference/Deprecated_and_obsolete_features](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Deprecated_and_obsolete_features)
#### Invalid AST transformations
##### td (31:4) => tableCell
```
type: "paragraph"
summary: "This page lists features of JavaScript that are deprecated (that is, still available but planned for removal) and obsolete (that is, no longer usable)."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "Parenthesized substring matches, if any."
  type: "break"
  type: "strong"
  children:
    type: "text"
    value: "Warning:"
  type: "text"
  value: " Using these properties can result in problems, since browser extensions can modify them. Avoid them!"
```
##### tr (29:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Parenthesized substring matches, if any.<br /><strong>Warning:</strong>\n    Using these properties can result in problems, since browser extensions can\n    modify them. Avoid them!\n  </p>\n</td>\n"
```
##### table.standard-table (23:1) => table
```
type: "html"
value: "<tr>\n  <td>{{anN4cmVmKCJSZWdFeHAubiIsICIkMS0kOSIp}}</td>\n  <td>\n    <p>\n      Parenthesized substring matches, if any.<br /><strong>Warning:</strong>\n      Using these properties can result in problems, since browser extensions\n      can modify them. Avoid them!\n    </p>\n  </td>\n</tr>\n"
```
##### tr (251:3) => tableRow
```
type: "html"
value: "<td>Property</td>\n",type: "html"
value: "<td>Description</td>\n"
```
##### table.standard-table (249:1) => table
```
type: "html"
value: "<tr>\n  <td>Property</td>\n  <td>Description</td>\n</tr>\n"
```
### Missing conversion rules
- td (252:4)
- td (253:4)
### [/en-US/docs/Web/JavaScript/Reference/Errors/Unexpected_token](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Unexpected_token)
### Missing conversion rules
- pre.brush:.js.example-bad.line-numbers.language-js (58:1)
### [/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters)
### Missing conversion rules
- span.seoSummary (14:4)
### [/en-US/docs/Web/JavaScript/Reference/Functions/get](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/get)
### Missing conversion rules
- abbr[title="ECMAScript 5th edition"] (51:44)
### [/en-US/docs/Web/JavaScript/Reference/Functions/set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/set)
### Missing conversion rules
- abbr[title="ECMAScript 5th edition"] (50:44)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
### Missing conversion rules
- table.fullwidth-table.standard-table (210:1)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)
#### Invalid AST transformations
##### tr (181:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">first call</th>\n"
```
##### tr (189:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">second call</th>\n"
```
##### tr (197:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">third call</th>\n"
```
##### tr (205:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">fourth call</th>\n"
```
##### table.standard-table (169:1) => table
```
type: "html"
value: "<tr>\n  <th scope=\"row\">first call</th>\n  <td><code>0</code></td>\n  <td><code>1</code></td>\n  <td><code>1</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>1</code></td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">second call</th>\n  <td><code>1</code></td>\n  <td><code>2</code></td>\n  <td><code>2</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>3</code></td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">third call</th>\n  <td><code>3</code></td>\n  <td><code>3</code></td>\n  <td><code>3</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>6</code></td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">fourth call</th>\n  <td><code>6</code></td>\n  <td><code>4</code></td>\n  <td><code>4</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>10</code></td>\n</tr>\n"
```
##### tr (246:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">first call</th>\n"
```
##### tr (254:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">second call</th>\n"
```
##### tr (262:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">third call</th>\n"
```
##### tr (270:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">fourth call</th>\n"
```
##### tr (278:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">fifth call</th>\n"
```
##### table.standard-table (234:1) => table
```
type: "html"
value: "<tr>\n  <th scope=\"row\">first call</th>\n  <td><code>10</code></td>\n  <td><code>0</code></td>\n  <td><code>0</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>10</code></td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">second call</th>\n  <td><code>10</code></td>\n  <td><code>1</code></td>\n  <td><code>1</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>11</code></td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">third call</th>\n  <td><code>11</code></td>\n  <td><code>2</code></td>\n  <td><code>2</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>13</code></td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">fourth call</th>\n  <td><code>13</code></td>\n  <td><code>3</code></td>\n  <td><code>3</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>16</code></td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">fifth call</th>\n  <td><code>16</code></td>\n  <td><code>4</code></td>\n  <td><code>4</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>20</code></td>\n</tr>\n"
```
### Missing conversion rules
- th[scope="row"] (182:7)
- th[scope="row"] (190:7)
- th[scope="row"] (198:7)
- th[scope="row"] (206:7)
- th[scope="row"] (247:7)
- th[scope="row"] (255:7)
- th[scope="row"] (263:7)
- th[scope="row"] (271:7)
- th[scope="row"] (279:7)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/ReduceRight](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/ReduceRight)
#### Invalid AST transformations
##### tr (125:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">first call</th>\n"
```
##### tr (133:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">second call</th>\n"
```
##### tr (141:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">third call</th>\n"
```
##### tr (149:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">fourth call</th>\n"
```
##### table (113:1) => table
```
type: "html"
value: "<tr>\n  <th scope=\"row\">first call</th>\n  <td><code>4</code></td>\n  <td><code>3</code></td>\n  <td><code>3</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>7</code></td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">second call</th>\n  <td><code>7</code></td>\n  <td><code>2</code></td>\n  <td><code>2</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>9</code></td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">third call</th>\n  <td><code>9</code></td>\n  <td><code>1</code></td>\n  <td><code>1</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>10</code></td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">fourth call</th>\n  <td><code>10</code></td>\n  <td><code>0</code></td>\n  <td><code>0</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>10</code></td>\n</tr>\n"
```
##### tr (183:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">first call</th>\n"
```
##### tr (191:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">second call</th>\n"
```
##### tr (199:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">third call</th>\n"
```
##### tr (207:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">fourth call</th>\n"
```
##### tr (215:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">fifth call</th>\n"
```
##### table (171:1) => table
```
type: "html"
value: "<tr>\n  <th scope=\"row\">first call</th>\n  <td><code>10</code></td>\n  <td><code>4</code></td>\n  <td><code>4</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>14</code></td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">second call</th>\n  <td><code>14</code></td>\n  <td><code>3</code></td>\n  <td><code>3</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>17</code></td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">third call</th>\n  <td><code>17</code></td>\n  <td><code>2</code></td>\n  <td><code>2</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>19</code></td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">fourth call</th>\n  <td><code>19</code></td>\n  <td><code>1</code></td>\n  <td><code>1</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>20</code></td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">fifth call</th>\n  <td><code>20</code></td>\n  <td><code>0</code></td>\n  <td><code>0</code></td>\n  <td><code>[0, 1, 2, 3, 4]</code></td>\n  <td><code>20</code></td>\n</tr>\n"
```
### Missing conversion rules
- th[scope="row"] (126:7)
- th[scope="row"] (134:7)
- th[scope="row"] (142:7)
- th[scope="row"] (150:7)
- th[scope="row"] (184:7)
- th[scope="row"] (192:7)
- th[scope="row"] (200:7)
- th[scope="row"] (208:7)
- th[scope="row"] (216:7)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/DataView/setBigInt64](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/DataView/setBigInt64)
### Missing conversion rules
- span.blob-code-inner.blob-code-marker (39:92)
- span.blob-code-inner.blob-code-marker (41:79)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/DataView/setBigUint64](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/DataView/setBigUint64)
### Missing conversion rules
- span.blob-code-inner.blob-code-marker (39:86)
- span.blob-code-inner.blob-code-marker (41:49)
- span.blob-code-inner.blob-code-marker (43:30)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/getTimezoneOffset](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/getTimezoneOffset)
#### Invalid AST transformations
##### tr (37:3) => tableRow
```
type: "html"
value: "<th scope=\"row\">Current time zone</th>\n"
```
##### tr (45:3) => tableRow
```
type: "html"
value: "<th scope=\"row\">Return Value</th>\n"
```
##### table.standard-table (35:1) => table
```
type: "html"
value: "<tr>\n  <th scope=\"row\">Current time zone</th>\n  <th scope=\"col\">UTC-8</th>\n  <th scope=\"col\">UTC</th>\n  <th scope=\"col\">UTC+3</th>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Return Value</th>\n  <td>480</td>\n  <td>0</td>\n  <td>-180</td>\n</tr>\n"
```
### Missing conversion rules
- th[scope="row"] (38:4)
- th[scope="row"] (46:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/arguments](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/arguments)
#### Invalid AST transformations
##### code (15:8) => text
```
type: "element"
tagName: "em"
properties:

children:
  type: "text"
  value: "function"
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/displayName](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/displayName)
#### Invalid AST transformations
##### code (14:8) => text
```
type: "element"
tagName: "em"
properties:

children:
  type: "text"
  value: "function"
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/Function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/Function)
### Missing conversion rules
- span.seoSummary (14:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/toString](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/toString)
#### Invalid AST transformations
##### td (78:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "function f(){}"
```
##### td (82:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "\"function f(){}\""
```
##### tr (77:9) => tableRow
```
type: "html"
value: "<td><pre class=\"brush: js\">function f(){}</pre></td>\n",type: "html"
value: "<td><pre class=\"brush: js\">\"function f(){}\"</pre></td>\n"
```
##### td (88:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "class A { a(){} }"
```
##### td (92:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "\"class A { a(){} }\""
```
##### tr (87:9) => tableRow
```
type: "html"
value: "<td><pre class=\"brush: js\">class A { a(){} }</pre></td>\n",type: "html"
value: "<td><pre class=\"brush: js\">\"class A { a(){} }\"</pre></td>\n"
```
##### td (98:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "function* g(){}"
```
##### td (102:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "\"function* g(){}\""
```
##### tr (97:9) => tableRow
```
type: "html"
value: "<td><pre class=\"brush: js\">function* g(){}</pre></td>\n",type: "html"
value: "<td><pre class=\"brush: js\">\"function* g(){}\"</pre></td>\n"
```
##### td (108:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "a => a"
```
##### td (112:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "\"a => a\""
```
##### tr (107:9) => tableRow
```
type: "html"
value: "<td><pre class=\"brush: js\">a => a</pre></td>\n",type: "html"
value: "<td><pre class=\"brush: js\">\"a => a\"</pre></td>\n"
```
##### td (118:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "({ a(){} }.a)"
```
##### td (122:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "\"a(){}\""
```
##### tr (117:9) => tableRow
```
type: "html"
value: "<td><pre class=\"brush: js\">({ a(){} }.a)</pre></td>\n",type: "html"
value: "<td><pre class=\"brush: js\">\"a(){}\"</pre></td>\n"
```
##### td (128:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "({ *a(){} }.a)"
```
##### td (132:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "\"*a(){}\""
```
##### tr (127:9) => tableRow
```
type: "html"
value: "<td><pre class=\"brush: js\">({ *a(){} }.a)</pre></td>\n",type: "html"
value: "<td><pre class=\"brush: js\">\"*a(){}\"</pre></td>\n"
```
##### td (138:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "({ [0](){} }[0])"
```
##### td (142:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "\"[0](){}\""
```
##### tr (137:9) => tableRow
```
type: "html"
value: "<td><pre class=\"brush: js\">({ [0](){} }[0])</pre></td>\n",type: "html"
value: "<td><pre class=\"brush: js\">\"[0](){}\"</pre></td>\n"
```
##### td (148:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "Object.getOwnPropertyDescriptor({     get a(){} }, \"a\").get"
```
##### td (154:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "\"get a(){}\""
```
##### tr (147:9) => tableRow
```
type: "html"
value: "<td>\n  <pre class=\"brush: js\">\nObject.getOwnPropertyDescriptor({\n    get a(){}\n}, \"a\").get</pre\n  >\n</td>\n",type: "html"
value: "<td><pre class=\"brush: js\">\"get a(){}\"</pre></td>\n"
```
##### td (160:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "Object.getOwnPropertyDescriptor({     set a(x){} }, \"a\").set"
```
##### td (166:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "\"set a(x){}\""
```
##### tr (159:9) => tableRow
```
type: "html"
value: "<td>\n  <pre class=\"brush: js\">\nObject.getOwnPropertyDescriptor({\n    set a(x){}\n}, \"a\").set</pre\n  >\n</td>\n",type: "html"
value: "<td><pre class=\"brush: js\">\"set a(x){}\"</pre></td>\n"
```
##### td (172:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "Function.prototype.toString"
```
##### td (176:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "\"function toString() { [native code] }\""
```
##### tr (171:9) => tableRow
```
type: "html"
value: "<td><pre class=\"brush: js\">Function.prototype.toString</pre></td>\n",type: "html"
value: "<td><pre class=\"brush: js\">\"function toString() { [native code] }\"</pre></td>\n"
```
##### td (182:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "(function f(){}.bind(0))"
```
##### td (186:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "\"function () { [native code] }\""
```
##### tr (181:9) => tableRow
```
type: "html"
value: "<td><pre class=\"brush: js\">(function f(){}.bind(0))</pre></td>\n",type: "html"
value: "<td><pre class=\"brush: js\">\"function () { [native code] }\"</pre></td>\n"
```
##### td (192:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "Function(\"a\", \"b\")"
```
##### td (196:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "\"function anonymous(a\\n) {\\nb\\n}\""
```
##### tr (191:9) => tableRow
```
type: "html"
value: "<td><pre class=\"brush: js\">Function(\"a\", \"b\")</pre></td>\n",type: "html"
value: "<td><pre class=\"brush: js\">\"function anonymous(a\\n) {\\nb\\n}\"</pre></td>\n"
```
##### table.standard-table (69:1) => table
```
type: "html"
value: "<tr>\n  <td><pre class=\"brush: js\">function f(){}</pre></td>\n  <td><pre class=\"brush: js\">\"function f(){}\"</pre></td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><pre class=\"brush: js\">class A { a(){} }</pre></td>\n  <td><pre class=\"brush: js\">\"class A { a(){} }\"</pre></td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><pre class=\"brush: js\">function* g(){}</pre></td>\n  <td><pre class=\"brush: js\">\"function* g(){}\"</pre></td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><pre class=\"brush: js\">a => a</pre></td>\n  <td><pre class=\"brush: js\">\"a => a\"</pre></td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><pre class=\"brush: js\">({ a(){} }.a)</pre></td>\n  <td><pre class=\"brush: js\">\"a(){}\"</pre></td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><pre class=\"brush: js\">({ *a(){} }.a)</pre></td>\n  <td><pre class=\"brush: js\">\"*a(){}\"</pre></td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><pre class=\"brush: js\">({ [0](){} }[0])</pre></td>\n  <td><pre class=\"brush: js\">\"[0](){}\"</pre></td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <pre class=\"brush: js\">\nObject.getOwnPropertyDescriptor({\n    get a(){}\n}, \"a\").get</pre\n    >\n  </td>\n  <td><pre class=\"brush: js\">\"get a(){}\"</pre></td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <pre class=\"brush: js\">\nObject.getOwnPropertyDescriptor({\n    set a(x){}\n}, \"a\").set</pre\n    >\n  </td>\n  <td><pre class=\"brush: js\">\"set a(x){}\"</pre></td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><pre class=\"brush: js\">Function.prototype.toString</pre></td>\n  <td><pre class=\"brush: js\">\"function toString() { [native code] }\"</pre></td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><pre class=\"brush: js\">(function f(){}.bind(0))</pre></td>\n  <td><pre class=\"brush: js\">\"function () { [native code] }\"</pre></td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><pre class=\"brush: js\">Function(\"a\", \"b\")</pre></td>\n  <td><pre class=\"brush: js\">\"function anonymous(a\\n) {\\nb\\n}\"</pre></td>\n</tr>\n"
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator/throw](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator/throw)
#### Invalid AST transformations
##### dl (36:1) => paragraph
```
type: "list"
ordered: false
start:

spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "Has the value "
      type: "inlineCode"
      value: "true"
      type: "text"
      value: " if the iterator is past the end of the iterated\nsequence. In this case "
      type: "inlineCode"
      value: "value"
      type: "text"
      value: " optionally specifies the "
      type: "emphasis"
      children:
        type: "text"
        value: "return\nvalue"
      type: "text"
      value: " of the iterator."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "text"
      value: "Has the value "
      type: "inlineCode"
      value: "false"
      type: "text"
      value: " if the iterator was able to produce the next\nvalue in the sequence. This is equivalent of not specifying the "
      type: "inlineCode"
      value: "done"
      type: "text"
      value: "\nproperty altogether."
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/DateTimeFormat/DateTimeFormat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/DateTimeFormat/DateTimeFormat)
### Missing conversion rules
- p.noinclude (261:3)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/calendar](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/calendar)
#### Invalid AST transformations
##### td (108:4) => tableCell
```
type: "blockquote"
children:
  type: "paragraph"
  children:
    type: "strong"
    children:
      type: "text"
      value: "Warning:"
    type: "text"
    value: " The "
    type: "inlineCode"
    value: "islamicc"
    type: "text"
    value: " calendar key has been deprecated. Please use "
    type: "inlineCode"
    value: "islamic-civil"
    type: "text"
    value: ".",type: "paragraph"
summary: "The Intl.Locale.prototype.calendar property is an accessor property which returns the type of calendar used in the Locale."
rowIndex: 19
shouldWrap: true
children:
  type: "inlineCode"
  value: "islamicc"
```
##### tr (107:3) => tableRow
```
type: "html"
value: "<td>\n  <div class=\"notecard warning\">\n    <p>\n      <strong>Warning:</strong> The <code>islamicc</code> calendar key has been\n      deprecated. Please use <code>islamic-civil</code>.\n    </p>\n  </div>\n  <p><code>islamicc</code></p>\n</td>\n"
```
##### table.standard-table (26:1) => table
```
type: "html"
value: "<tr>\n  <td>\n    <div class=\"notecard warning\">\n      <p>\n        <strong>Warning:</strong> The <code>islamicc</code> calendar key has\n        been deprecated. Please use <code>islamic-civil</code>.\n      </p>\n    </div>\n    <p><code>islamicc</code></p>\n  </td>\n  <td>Civil (algorithmic) Arabic calendar</td>\n</tr>\n"
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/collation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/collation)
#### Invalid AST transformations
##### td (49:4) => tableCell
```
type: "blockquote"
children:
  type: "paragraph"
  children:
    type: "strong"
    children:
      type: "text"
      value: "Warning:"
    type: "text"
    value: " The "
    type: "inlineCode"
    value: "direct"
    type: "text"
    value: " collation type has been deprected. Do not use.",type: "paragraph"
summary: "The Intl.Locale.prototype.collation property is an accessor property that returns the collation type for the Locale, which is used to order strings according to the locale's rules."
rowIndex: 4
shouldWrap: true
children:
  type: "text"
  value: "direct"
```
##### tr (48:3) => tableRow
```
type: "html"
value: "<td>\n  <div class=\"notecard warning\">\n    <p>\n      <strong>Warning:</strong> The <code>direct</code> collation type has been\n      deprected. Do not use.\n    </p>\n  </div>\n  <p>direct</p>\n</td>\n"
```
##### td (115:4) => tableCell
```
type: "paragraph"
summary: "The Intl.Locale.prototype.collation property is an accessor property that returns the collation type for the Locale, which is used to order strings according to the locale's rules."
rowIndex: 19
shouldWrap: true
children:
  type: "text"
  value: "Pinyin ordering for Latin, zhuyin order for Bopomofo and CJK characters (used in Chinese)"
```
##### tr (113:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    Pinyin ordering for Latin, zhuyin order for Bopomofo and CJK characters\n    (used in Chinese)\n  </p>\n</td>\n"
```
##### table.standard-table (28:1) => table
```
type: "html"
value: "<tr>\n  <td>\n    <div class=\"notecard warning\">\n      <p>\n        <strong>Warning:</strong> The <code>direct</code> collation type has\n        been deprected. Do not use.\n      </p>\n    </div>\n    <p>direct</p>\n  </td>\n  <td>Binary code point order (used in Hindi)</td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>zhuyin</td>\n  <td>\n    <p>\n      Pinyin ordering for Latin, zhuyin order for Bopomofo and CJK characters\n      (used in Chinese)\n    </p>\n  </td>\n</tr>\n"
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/maximize](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/maximize)
### Missing conversion rules
- span.seoSummary (17:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/minimize](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/minimize)
### Missing conversion rules
- span.seoSummary (16:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/toString](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Locale/toString)
### Missing conversion rules
- span.seoSummary (17:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map/@@iterator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map/@@iterator)
### Missing conversion rules
- p.seoSummary (17:1)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map)
#### Invalid AST transformations
##### tr (54:5) => tableRow
```
type: "html"
value: "<th scope=\"row\"></th>\n"
```
##### td (65:7) => tableCell
```
type: "paragraph"
summary: "The Map object holds key-value\n    pairs and remembers the original insertion order of the keys. Any value (both\n  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key\n  or a value."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "An "
  type: "inlineCode"
  value: "Object"
  type: "text"
  value: " has a prototype, so it contains default keys that could collide with your own keys if you're not careful.",type: "blockquote"
children:
  type: "paragraph"
  children:
    type: "strong"
    children:
      type: "text"
      value: "Note:"
    type: "text"
    value: " As of ES5, this can be bypassed by using {{anN4cmVmKCJPYmplY3QuY3JlYXRlIiwgIk9iamVjdC5jcmVhdGUobnVsbCkiKQ==}}, but this is seldom done."
```
##### tr (61:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">Accidental Keys</th>\n",type: "html"
value: "<td>\n  <p>\n    An <code>Object</code> has a prototype, so it contains default keys that\n    could collide with your own keys if you're not careful.\n  </p>\n  <div class=\"notecard note\">\n    <p>\n      <strong>Note:</strong> As of ES5, this can be bypassed by using\n      {{anN4cmVmKCJPYmplY3QuY3JlYXRlIiwgIk9iamVjdC5jcmVhdGUobnVsbCkiKQ==}}, but\n      this is seldom done.\n    </p>\n  </div>\n</td>\n"
```
##### tr (76:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">Key Types</th>\n"
```
##### td (85:7) => tableCell
```
type: "paragraph"
summary: "The Map object holds key-value\n    pairs and remembers the original insertion order of the keys. Any value (both\n  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key\n  or a value."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "The keys in "
  type: "inlineCode"
  value: "Map"
  type: "text"
  value: " are ordered in a simple, straightforward way: A "
  type: "inlineCode"
  value: "Map"
  type: "text"
  value: " object iterates entries, keys, and values in the order of entry insertion."
```
##### td (90:7) => tableCell
```
type: "paragraph"
summary: "The Map object holds key-value\n    pairs and remembers the original insertion order of the keys. Any value (both\n  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key\n  or a value."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "Although the keys of an ordinary "
  type: "inlineCode"
  value: "Object"
  type: "text"
  value: " are ordered now, this was not always the case, and the order is complex. As a result, it's best not to rely on property order.",type: "paragraph"
summary: "The Map object holds key-value\n    pairs and remembers the original insertion order of the keys. Any value (both\n  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key\n  or a value."
rowIndex: 3
shouldWrap: true
children:
  type: "text"
  value: "The order was first defined for own properties only in ECMAScript 2015; ECMAScript 2020 defines order for inherited properties as well. See the "
  type: "link"
  title:

  url: "https://tc39.es/ecma262/#sec-ordinaryownpropertykeys"
  children:
    type: "text"
    value: "OrdinaryOwnPropertyKeys"
  type: "text"
  value: " and "
  type: "link"
  title:

  url: "https://tc39.es/ecma262/#sec-enumerate-object-properties"
  children:
    type: "text"
    value: "EnumerateObjectProperties"
  type: "text"
  value: " abstract specification operations. But note that no single mechanism iterates "
  type: "strong"
  children:
    type: "text"
    value: "all"
  type: "text"
  value: " of an object's properties; the various mechanisms each include different subsets of properties. ({{anN4cmVmKCJTdGF0ZW1lbnRzL2Zvci4uLmluIiwKICAgICAgICAgICJmb3ItaW4iKQ==}} includes only enumerable string-keyed properties; {{anN4cmVmKCJPYmplY3Qua2V5cyIp}} includes only own, enumerable, string-keyed properties; {{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlOYW1lcyIp}} includes own, string-keyed properties even if non-enumerable; {{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlTeW1ib2xzIik=}} does the same for just "
  type: "inlineCode"
  value: "Symbol"
  type: "text"
  value: "-keyed properties, etc.)"
```
##### tr (83:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">Key Order</th>\n",type: "html"
value: "<td>\n  <p>\n    The keys in <code>Map</code> are ordered in a simple, straightforward way: A\n    <code>Map</code> object iterates entries, keys, and values in the order of\n    entry insertion.\n  </p>\n</td>\n",type: "html"
value: "<td>\n  <p>\n    Although the keys of an ordinary <code>Object</code> are ordered now, this\n    was not always the case, and the order is complex. As a result, it's best\n    not to rely on property order.\n  </p>\n  <p>\n    The order was first defined for own properties only in ECMAScript 2015;\n    ECMAScript 2020 defines order for inherited properties as well. See the\n    <a href=\"https://tc39.es/ecma262/#sec-ordinaryownpropertykeys\"\n      >OrdinaryOwnPropertyKeys</a\n    >\n    and\n    <a href=\"https://tc39.es/ecma262/#sec-enumerate-object-properties\"\n      >EnumerateObjectProperties</a\n    >\n    abstract specification operations. But note that no single mechanism\n    iterates\n    <strong>all</strong> of an object's properties; the various mechanisms each\n    include different subsets of properties.\n    ({{anN4cmVmKCJTdGF0ZW1lbnRzL2Zvci4uLmluIiwKICAgICAgICAgICJmb3ItaW4iKQ==}}\n    includes only enumerable string-keyed properties;\n    {{anN4cmVmKCJPYmplY3Qua2V5cyIp}} includes only own, enumerable, string-keyed\n    properties; {{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlOYW1lcyIp}} includes\n    own, string-keyed properties even if non-enumerable;\n    {{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlTeW1ib2xzIik=}} does the same for\n    just <code>Symbol</code>-keyed properties, etc.)\n  </p>\n</td>\n"
```
##### tr (108:5) => tableRow
```
type: "html"
value: "<th scope=\"row\"><p>Size</p></th>\n"
```
##### td (121:7) => tableCell
```
type: "paragraph"
summary: "The Map object holds key-value\n    pairs and remembers the original insertion order of the keys. Any value (both\n  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key\n  or a value."
rowIndex: 5
shouldWrap: true
children:
  type: "inlineCode"
  value: "Object"
  type: "text"
  value: " does not implement an "
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Iteration_protocols#the_iterable_protocol"
  children:
    type: "text"
    value: "iteration protocol"
  type: "text"
  value: ", and so objects are not directly iterable using the JavaScript "
  type: "link"
  title:

  url: "/en-US/docs/Web/JavaScript/Reference/Statements/for...of"
  children:
    type: "text"
    value: "for...of"
  type: "text"
  value: " statement (by default).",type: "blockquote"
children:
  type: "paragraph"
  children:
    type: "strong"
    children:
      type: "text"
      value: "Note:"
  type: "list"
  ordered: false
  start:

  spread: false
  children:
    type: "listItem"
    spread: false
    children:
      type: "paragraph"
      children:
        type: "text"
        value: "An object can implement the iteration protocol, or you can get an iterable for an object using "
        type: "link"
        title:

        url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys"
        children:
          type: "inlineCode"
          value: "Object.keys"
        type: "text"
        value: " or "
        type: "link"
        title:

        url: "/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries"
        children:
          type: "inlineCode"
          value: "Object.entries"
        type: "text"
        value: "."
    type: "listItem"
    spread: false
    children:
      type: "paragraph"
      children:
        type: "text"
        value: "The "
        type: "link"
        title:

        url: "/en-US/docs/Web/JavaScript/Reference/Statements/for...in"
        children:
          type: "text"
          value: "for...in"
        type: "text"
        value: " statement allows you to iterate over the "
        type: "emphasis"
        children:
          type: "text"
          value: "enumerable"
        type: "text"
        value: " properties of an object."
```
##### tr (116:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">Iteration</th>\n",type: "html"
value: "<td>\n  <p>\n    <code>Object</code> does not implement an <a\n      href=\"/en-US/docs/Web/JavaScript/Reference/Iteration_protocols#the_iterable_protocol\"\n      >iteration protocol</a\n    >, and so objects are not directly iterable using the JavaScript\n    <a href=\"/en-US/docs/Web/JavaScript/Reference/Statements/for...of\"\n      >for...of</a\n    >\n    statement (by default).\n  </p>\n  <div class=\"notecard note\">\n    <p><strong>Note:</strong></p>\n    <ul>\n      <li>\n        An object can implement the iteration protocol, or you can get an\n        iterable for an object using <a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys\"\n          ><code>Object.keys</code></a\n        > or <a\n          href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries\"\n          ><code>Object.entries</code></a\n        >.\n      </li>\n      <li>\n        The\n        <a href=\"/en-US/docs/Web/JavaScript/Reference/Statements/for...in\"\n          >for...in</a\n        >\n        statement allows you to iterate over the <em>enumerable</em> properties\n        of an object.\n      </li>\n    </ul>\n  </div>\n</td>\n"
```
##### td (147:7) => tableCell
```
type: "paragraph"
summary: "The Map object holds key-value\n    pairs and remembers the original insertion order of the keys. Any value (both\n  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key\n  or a value."
rowIndex: 6
shouldWrap: true
children:
  type: "text"
  value: "Performs better in scenarios involving frequent additions and removals of key-value pairs."
```
##### td (151:7) => tableCell
```
type: "paragraph"
summary: "The Map object holds key-value\n    pairs and remembers the original insertion order of the keys. Any value (both\n  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key\n  or a value."
rowIndex: 6
shouldWrap: true
children:
  type: "text"
  value: "Not optimized for frequent additions and removals of key-value pairs."
```
##### tr (145:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">Performance</th>\n",type: "html"
value: "<td>\n  <p>\n    Performs better in scenarios involving frequent additions and removals of\n    key-value pairs.\n  </p>\n</td>\n",type: "html"
value: "<td>\n  <p>Not optimized for frequent additions and removals of key-value pairs.</p>\n</td>\n"
```
##### td (157:7) => tableCell
```
type: "paragraph"
summary: "The Map object holds key-value\n    pairs and remembers the original insertion order of the keys. Any value (both\n  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key\n  or a value."
rowIndex: 7
shouldWrap: true
children:
  type: "text"
  value: "No native support for serialization or parsing.",type: "paragraph"
summary: "The Map object holds key-value\n    pairs and remembers the original insertion order of the keys. Any value (both\n  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key\n  or a value."
rowIndex: 7
shouldWrap: true
children:
  type: "text"
  value: "(But you can build your own serialization and parsing support for "
  type: "inlineCode"
  value: "Map"
  type: "text"
  value: " by using {{anN4cmVmKCJKU09OLnN0cmluZ2lmeSgpIik=}} with its "
  type: "emphasis"
  children:
    type: "text"
    value: "replacer"
  type: "text"
  value: " argument, and by using {{anN4cmVmKCJKU09OLnBhcnNlKCkiKQ==}} with its "
  type: "emphasis"
  children:
    type: "text"
    value: "reviver"
  type: "text"
  value: " argument. See the Stack Overflow question "
  type: "link"
  title:

  url: "https://stackoverflow.com/q/29085197/"
  children:
    type: "text"
    value: "How do you JSON.stringify an ES6 Map?"
  type: "text"
  value: ")."
```
##### td (161:7) => tableCell
```
type: "paragraph"
summary: "The Map object holds key-value\n    pairs and remembers the original insertion order of the keys. Any value (both\n  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key\n  or a value."
rowIndex: 7
shouldWrap: true
children:
  type: "text"
  value: "Native support for serialization from {{anN4cmVmKCJPYmplY3QiKQ==}} to JSON, using {{anN4cmVmKCJKU09OLnN0cmluZ2lmeSgpIik=}}.",type: "paragraph"
summary: "The Map object holds key-value\n    pairs and remembers the original insertion order of the keys. Any value (both\n  objects and {{Z2xvc3NhcnkoIlByaW1pdGl2ZSIsICJwcmltaXRpdmUgdmFsdWVzIik=}}) may be used as either a key\n  or a value."
rowIndex: 7
shouldWrap: true
children:
  type: "text"
  value: "Native support for parsing from JSON to {{anN4cmVmKCJPYmplY3QiKQ==}}, using {{anN4cmVmKCJKU09OLnBhcnNlKCkiKQ==}}."
```
##### tr (155:5) => tableRow
```
type: "html"
value: "<th scope=\"row\">Serialization and parsing</th>\n",type: "html"
value: "<td>\n  <p>No native support for serialization or parsing.</p>\n  <p>\n    (But you can build your own serialization and parsing support for\n    <code>Map</code> by using {{anN4cmVmKCJKU09OLnN0cmluZ2lmeSgpIik=}} with its\n    <em>replacer</em> argument, and by using\n    {{anN4cmVmKCJKU09OLnBhcnNlKCkiKQ==}} with its <em>reviver</em> argument. See\n    the Stack Overflow question\n    <a href=\"https://stackoverflow.com/q/29085197/\"\n      >How do you JSON.stringify an ES6 Map?</a\n    >).\n  </p>\n</td>\n",type: "html"
value: "<td>\n  <p>\n    Native support for serialization from {{anN4cmVmKCJPYmplY3QiKQ==}} to JSON,\n    using {{anN4cmVmKCJKU09OLnN0cmluZ2lmeSgpIik=}}.\n  </p>\n  <p>\n    Native support for parsing from JSON to {{anN4cmVmKCJPYmplY3QiKQ==}}, using\n    {{anN4cmVmKCJKU09OLnBhcnNlKCkiKQ==}}.\n  </p>\n</td>\n"
```
##### table.standard-table (52:1) => table
```
type: "html"
value: "<tr>\n  <th scope=\"row\"></th>\n  <th scope=\"col\">Map</th>\n  <th scope=\"col\">Object</th>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Accidental Keys</th>\n  <td>\n    A <code>Map</code> does not contain any keys by default. It only contains\n    what is explicitly put into it.\n  </td>\n  <td>\n    <p>\n      An <code>Object</code> has a prototype, so it contains default keys that\n      could collide with your own keys if you're not careful.\n    </p>\n    <div class=\"notecard note\">\n      <p>\n        <strong>Note:</strong> As of ES5, this can be bypassed by using\n        {{anN4cmVmKCJPYmplY3QuY3JlYXRlIiwgIk9iamVjdC5jcmVhdGUobnVsbCkiKQ==}},\n        but this is seldom done.\n      </p>\n    </div>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Key Types</th>\n  <td>\n    A <code>Map</code>'s keys can be any value (including functions, objects, or\n    any primitive).\n  </td>\n  <td>\n    The keys of an <code>Object</code> must be either a\n    {{anN4cmVmKCJTdHJpbmciKQ==}} or a {{anN4cmVmKCJTeW1ib2wiKQ==}}.\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Key Order</th>\n  <td>\n    <p>\n      The keys in <code>Map</code> are ordered in a simple, straightforward way:\n      A <code>Map</code> object iterates entries, keys, and values in the order\n      of entry insertion.\n    </p>\n  </td>\n  <td>\n    <p>\n      Although the keys of an ordinary <code>Object</code> are ordered now, this\n      was not always the case, and the order is complex. As a result, it's best\n      not to rely on property order.\n    </p>\n    <p>\n      The order was first defined for own properties only in ECMAScript 2015;\n      ECMAScript 2020 defines order for inherited properties as well. See the\n      <a href=\"https://tc39.es/ecma262/#sec-ordinaryownpropertykeys\"\n        >OrdinaryOwnPropertyKeys</a\n      >\n      and\n      <a href=\"https://tc39.es/ecma262/#sec-enumerate-object-properties\"\n        >EnumerateObjectProperties</a\n      >\n      abstract specification operations. But note that no single mechanism\n      iterates\n      <strong>all</strong> of an object's properties; the various mechanisms\n      each include different subsets of properties.\n      ({{anN4cmVmKCJTdGF0ZW1lbnRzL2Zvci4uLmluIiwKICAgICAgICAgICJmb3ItaW4iKQ==}}\n      includes only enumerable string-keyed properties;\n      {{anN4cmVmKCJPYmplY3Qua2V5cyIp}} includes only own, enumerable,\n      string-keyed properties;\n      {{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlOYW1lcyIp}} includes own,\n      string-keyed properties even if non-enumerable;\n      {{anN4cmVmKCJPYmplY3QuZ2V0T3duUHJvcGVydHlTeW1ib2xzIik=}} does the same for\n      just <code>Symbol</code>-keyed properties, etc.)\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\"><p>Size</p></th>\n  <td>\n    The number of items in a <code>Map</code> is easily retrieved from its\n    {{anN4cmVmKCJNYXAucHJvdG90eXBlLnNpemUiLCAic2l6ZSIp}} property.\n  </td>\n  <td>\n    The number of items in an <code>Object</code> must be determined manually.\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Iteration</th>\n  <td>\n    A <code>Map</code> is an\n    <a href=\"/en-US/docs/Web/JavaScript/Reference/Iteration_protocols\"\n      >iterable</a\n    >, so it can be directly iterated.\n  </td>\n  <td>\n    <p>\n      <code>Object</code> does not implement an <a\n        href=\"/en-US/docs/Web/JavaScript/Reference/Iteration_protocols#the_iterable_protocol\"\n        >iteration protocol</a\n      >, and so objects are not directly iterable using the JavaScript\n      <a href=\"/en-US/docs/Web/JavaScript/Reference/Statements/for...of\"\n        >for...of</a\n      >\n      statement (by default).\n    </p>\n    <div class=\"notecard note\">\n      <p><strong>Note:</strong></p>\n      <ul>\n        <li>\n          An object can implement the iteration protocol, or you can get an\n          iterable for an object using <a\n            href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys\"\n            ><code>Object.keys</code></a\n          > or <a\n            href=\"/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries\"\n            ><code>Object.entries</code></a\n          >.\n        </li>\n        <li>\n          The\n          <a href=\"/en-US/docs/Web/JavaScript/Reference/Statements/for...in\"\n            >for...in</a\n          >\n          statement allows you to iterate over the\n          <em>enumerable</em> properties of an object.\n        </li>\n      </ul>\n    </div>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Performance</th>\n  <td>\n    <p>\n      Performs better in scenarios involving frequent additions and removals of\n      key-value pairs.\n    </p>\n  </td>\n  <td>\n    <p>Not optimized for frequent additions and removals of key-value pairs.</p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <th scope=\"row\">Serialization and parsing</th>\n  <td>\n    <p>No native support for serialization or parsing.</p>\n    <p>\n      (But you can build your own serialization and parsing support for\n      <code>Map</code> by using {{anN4cmVmKCJKU09OLnN0cmluZ2lmeSgpIik=}} with\n      its <em>replacer</em> argument, and by using\n      {{anN4cmVmKCJKU09OLnBhcnNlKCkiKQ==}} with its <em>reviver</em> argument.\n      See the Stack Overflow question\n      <a href=\"https://stackoverflow.com/q/29085197/\"\n        >How do you JSON.stringify an ES6 Map?</a\n      >).\n    </p>\n  </td>\n  <td>\n    <p>\n      Native support for serialization from {{anN4cmVmKCJPYmplY3QiKQ==}} to\n      JSON, using {{anN4cmVmKCJKU09OLnN0cmluZ2lmeSgpIik=}}.\n    </p>\n    <p>\n      Native support for parsing from JSON to {{anN4cmVmKCJPYmplY3QiKQ==}},\n      using {{anN4cmVmKCJKU09OLnBhcnNlKCkiKQ==}}.\n    </p>\n  </td>\n</tr>\n"
```
### Missing conversion rules
- th[scope="row"] (55:7)
- th[scope="row"] (62:7)
- th[scope="row"] (77:7)
- th[scope="row"] (84:7)
- th[scope="row"] (109:7)
- th[scope="row"] (117:7)
- th[scope="row"] (146:7)
- th[scope="row"] (156:7)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math)
### Missing conversion rules
- sub (91:38)
- sub (93:38)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/min](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/min)
### Missing conversion rules
- span.seoSummary (21:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/isSafeInteger](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/isSafeInteger)
### Missing conversion rules
- dfn (16:40)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign)
### Missing conversion rules
- span.seoSummary (16:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/defineProperty](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/defineProperty)
### Missing conversion rules
- dfn (53:31)
- dfn (54:51)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyDescriptor](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyDescriptor)
### Missing conversion rules
- dfn (45:3)
- dfn (50:6)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyDescriptors](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyDescriptors)
### Missing conversion rules
- dfn (38:13)
- dfn (43:6)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/Comparing_Reflect_and_Object_methods](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/Comparing_Reflect_and_Object_methods)
#### Invalid AST transformations
##### td (77:4) => tableCell
```
type: "paragraph"
summary: "The {{anN4cmVmKCJSZWZsZWN0Iik=}} object, introduced in ES2015, is a built-in object that provides methods to interface with JavaScript objects. Some of the static functions that exist on Reflect also correspond to methods available on {{anN4cmVmKCJPYmplY3QiKQ==}}, which predates ES2015. Although some of the methods appear to be similar in their behavior, there are often subtle differences between them."
rowIndex: 10
shouldWrap: true
children:
  type: "text"
  value: "{{anN4cmVmKCJSZWZsZWN0LmlzRXh0ZW5zaWJsZSgpIik=}} returns "
  type: "inlineCode"
  value: "true"
  type: "text"
  value: " if the object is extensible, and "
  type: "inlineCode"
  value: "false"
  type: "text"
  value: " if it is not. Throws a "
  type: "inlineCode"
  value: "TypeError"
  type: "text"
  value: " if the first argument is not an object (a primitive)."
```
##### tr (74:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    {{anN4cmVmKCJSZWZsZWN0LmlzRXh0ZW5zaWJsZSgpIik=}}\n    returns <code>true</code> if the object is extensible,\n    and <code>false</code> if it is not. Throws a <code>TypeError</code> if the\n    first argument is not an object (a primitive).\n  </p>\n</td>\n"
```
##### td (83:4) => tableCell
```
type: "paragraph"
summary: "The {{anN4cmVmKCJSZWZsZWN0Iik=}} object, introduced in ES2015, is a built-in object that provides methods to interface with JavaScript objects. Some of the static functions that exist on Reflect also correspond to methods available on {{anN4cmVmKCJPYmplY3QiKQ==}}, which predates ES2015. Although some of the methods appear to be similar in their behavior, there are often subtle differences between them."
rowIndex: 11
shouldWrap: true
children:
  type: "text"
  value: "{{anN4cmVmKCJPYmplY3QucHJldmVudEV4dGVuc2lvbnMoKSIp}} returns the object that is being made non-extensible. Throws a "
  type: "inlineCode"
  value: "TypeError"
  type: "text"
  value: "in ES5 if the argument is not an object (a primitive). In ES2015, treats the argument as a non-extensible, ordinary object and returns the object itself."
```
##### tr (81:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    {{anN4cmVmKCJPYmplY3QucHJldmVudEV4dGVuc2lvbnMoKSIp}} returns the object that\n    is being made non-extensible. Throws a <code>TypeError</code>in ES5 if the\n    argument is not an object (a primitive). In ES2015, treats the argument as a\n    non-extensible, ordinary object and returns the object itself.\n  </p>\n</td>\n"
```
##### table.standard-table (20:1) => table
```
type: "html"
value: "<tr>\n  <td><code>isExtensible()</code></td>\n  <td>\n    {{anN4cmVmKCJPYmplY3QuaXNFeHRlbnNpYmxlKCkiKQ==}}\n    returns <code>true</code> if the object is extensible,\n    and <code>false</code> if it is not. Throws a <code>TypeError</code> in ES5\n    if the first argument is not an object (a primitive). In ES2015, it will be\n    coerced into a non-extensible, ordinary object and will\n    return <code>false</code>.\n  </td>\n  <td>\n    <p>\n      {{anN4cmVmKCJSZWZsZWN0LmlzRXh0ZW5zaWJsZSgpIik=}}\n      returns <code>true</code> if the object is extensible,\n      and <code>false</code> if it is not. Throws a <code>TypeError</code> if\n      the first argument is not an object (a primitive).\n    </p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>preventExtensions()</code></td>\n  <td>\n    <p>\n      {{anN4cmVmKCJPYmplY3QucHJldmVudEV4dGVuc2lvbnMoKSIp}} returns the object\n      that is being made non-extensible. Throws a <code>TypeError</code>in ES5\n      if the argument is not an object (a primitive). In ES2015, treats the\n      argument as a non-extensible, ordinary object and returns the object\n      itself.\n    </p>\n  </td>\n  <td>\n    {{anN4cmVmKCJSZWZsZWN0LnByZXZlbnRFeHRlbnNpb25zKCkiKQ==}}\n    returns <code>true</code> if the object has been made non-extensible,\n    and <code>false</code> if it has not. Throws a <code>TypeError</code> if the\n    argument is not an object (a primitive).\n  </td>\n</tr>\n"
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/getOwnPropertyDescriptor](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/getOwnPropertyDescriptor)
### Missing conversion rules
- span.seoSummary (16:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/isExtensible](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Reflect/isExtensible)
### Missing conversion rules
- span.seoSummary (16:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/exec](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/exec)
#### Invalid AST transformations
##### td (90:7) => tableCell
```
type: "paragraph"
summary: "The exec() method executes a\n    search for a match in a specified string. Returns a result array, or\n    {{anN4cmVmKCJudWxsIik=}}."
rowIndex: 2
shouldWrap: true
children:
  type: "text"
  value: "The parenthesized substring matches, if any.",type: "paragraph"
summary: "The exec() method executes a\n    search for a match in a specified string. Returns a result array, or\n    {{anN4cmVmKCJudWxsIik=}}."
rowIndex: 2
shouldWrap: true
children:
  type: "text"
  value: "The number of possible parenthesized substrings is unlimited."
```
##### td (95:7) => tableCell
```
type: "paragraph"
summary: "The exec() method executes a\n    search for a match in a specified string. Returns a result array, or\n    {{anN4cmVmKCJudWxsIik=}}."
rowIndex: 2
shouldWrap: true
children:
  type: "inlineCode"
  value: "result[1] === \"Brown\"",type: "paragraph"
summary: "The exec() method executes a\n    search for a match in a specified string. Returns a result array, or\n    {{anN4cmVmKCJudWxsIik=}}."
rowIndex: 2
shouldWrap: true
children:
  type: "inlineCode"
  value: "result[2] === \"Jumps\""
```
##### tr (88:5) => tableRow
```
type: "html"
value: "<td>\n  <p>The parenthesized substring matches, if any.</p>\n  <p>The number of possible parenthesized substrings is unlimited.</p>\n</td>\n",type: "html"
value: "<td>\n  <p><code>result[1] === \"Brown\"</code></p>\n  <p><code>result[2] === \"Jumps\"</code></p>\n</td>\n"
```
##### td (118:7) => tableCell
```
type: "paragraph"
summary: "The exec() method executes a\n    search for a match in a specified string. Returns a result array, or\n    {{anN4cmVmKCJudWxsIik=}}."
rowIndex: 4
shouldWrap: true
children:
  type: "inlineCode"
  value: "indices[0] === Array [ 4, 25 ]",type: "paragraph"
summary: "The exec() method executes a\n    search for a match in a specified string. Returns a result array, or\n    {{anN4cmVmKCJudWxsIik=}}."
rowIndex: 4
shouldWrap: true
children:
  type: "inlineCode"
  value: "indices[1] === Array [ 10, 15 ]",type: "paragraph"
summary: "The exec() method executes a\n    search for a match in a specified string. Returns a result array, or\n    {{anN4cmVmKCJudWxsIik=}}."
rowIndex: 4
shouldWrap: true
children:
  type: "inlineCode"
  value: "indices[2] === Array [ 20, 25 ]",type: "paragraph"
summary: "The exec() method executes a\n    search for a match in a specified string. Returns a result array, or\n    {{anN4cmVmKCJudWxsIik=}}."
rowIndex: 4
shouldWrap: true
children:
  type: "inlineCode"
  value: "indices.groups === undefined",type: "paragraph"
summary: "The exec() method executes a\n    search for a match in a specified string. Returns a result array, or\n    {{anN4cmVmKCJudWxsIik=}}."
rowIndex: 4
shouldWrap: true
children:
  type: "inlineCode"
  value: "indices.length === 3"
```
##### tr (106:5) => tableRow
```
type: "html"
value: "<td>\n  <p><code>indices[0] === Array [ 4, 25 ]</code></p>\n  <p><code>indices[1] === Array [ 10, 15 ]</code></p>\n  <p><code>indices[2] === Array [ 20, 25 ]</code></p>\n  <p><code>indices.groups === undefined</code></p>\n  <p><code>indices.length === 3</code></p>\n</td>\n"
```
##### table.standard-table (74:1) => table
```
type: "html"
value: "<tr>\n  <td><code>[1], ...[<var>n</var>]</code></td>\n  <td>\n    <p>The parenthesized substring matches, if any.</p>\n    <p>The number of possible parenthesized substrings is unlimited.</p>\n  </td>\n  <td>\n    <p><code>result[1] === \"Brown\"</code></p>\n    <p><code>result[2] === \"Jumps\"</code></p>\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td><code>indices</code></td>\n  <td>\n    An array where each entry represents a substring match. Each substring match\n    itself is an array where the first entry represents its start index and the\n    second entry its end index.<br />The <code>indices</code> array additionally\n    has a <code>groups</code> property which holds an object of all named\n    capturing groups. The keys are the names of the capturing groups and each\n    value is an array with the first item being the start entry and the second\n    entry being the end index of the capturing group. If the regular expression\n    doesn't contain any capturing groups, <code>groups</code> is\n    <code>undefined</code>.\n  </td>\n  <td>\n    <p><code>indices[0] === Array [ 4, 25 ]</code></p>\n    <p><code>indices[1] === Array [ 10, 15 ]</code></p>\n    <p><code>indices[2] === Array [ 20, 25 ]</code></p>\n    <p><code>indices.groups === undefined</code></p>\n    <p><code>indices.length === 3</code></p>\n  </td>\n</tr>\n"
```
##### td (147:7) => tableCell
```
type: "paragraph"
summary: "The exec() method executes a\n    search for a match in a specified string. Returns a result array, or\n    {{anN4cmVmKCJudWxsIik=}}."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "The index at which to start the next match.",type: "paragraph"
summary: "The exec() method executes a\n    search for a match in a specified string. Returns a result array, or\n    {{anN4cmVmKCJudWxsIik=}}."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "If "
  type: "inlineCode"
  value: "g"
  type: "text"
  value: " is absent, this will always be "
  type: "inlineCode"
  value: "0"
  type: "text"
  value: "."
```
##### tr (145:5) => tableRow
```
type: "html"
value: "<td>\n  <p>The index at which to start the next match.</p>\n  <p>If <code>g</code> is absent, this will always be <code>0</code>.</p>\n</td>\n"
```
##### table.standard-table (136:1) => table
```
type: "html"
value: "<tr>\n  <td><code>lastIndex</code></td>\n  <td>\n    <p>The index at which to start the next match.</p>\n    <p>If <code>g</code> is absent, this will always be <code>0</code>.</p>\n  </td>\n  <td><code>25</code></td>\n</tr>\n"
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set)
### Missing conversion rules
- pre.brush:.js[dir="ltr"] (263:1)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/charAt](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/charAt)
### Missing conversion rules
- span.seoSummary (15:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/endsWith](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/endsWith)
### Missing conversion rules
- span.seoSummary (16:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)
### Missing conversion rules
- kbd (44:48)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/indexOf](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/indexOf)
### Missing conversion rules
- span.seoSummary (15:4)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/trimEnd](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/trimEnd)
### Missing conversion rules
- pre.brush:.js.highlight:.[5] (51:1)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/trimStart](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/trimStart)
### Missing conversion rules
- pre.brush:.js.highlight:.[5] (51:1)
- pre.brush:.js.highlight:.[5] (62:1)
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/name](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray/name)
#### Invalid AST transformations
##### code (14:8) => text
```
type: "element"
tagName: "em"
properties:

children:
  type: "text"
  value: "TypedArray"
```
### [/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap/clear](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap/clear)
### Missing conversion rules
- pre.brush:.js;highlight:[10].example-bad (27:1)
### [/en-US/docs/Web/JavaScript/Reference/Iteration_protocols](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Iteration_protocols)
#### Invalid AST transformations
##### td (63:4) => tableCell
```
type: "paragraph"
summary: "As a couple of additions to ECMAScript 2015, Iteration protocols aren't new built-ins or syntax, but protocols. These protocols can be implemented by any object by following some conventions."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "A function, with either zero arguments or one argument, that returns an object with at least the following two properties. If the "
  type: "inlineCode"
  value: "next()"
  type: "text"
  value: " method is called with one argument, that argument will be available to the "
  type: "inlineCode"
  value: "next()"
  type: "text"
  value: " method being invoked.",type: "list"
spread: false
children:
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "inlineCode"
      value: "done"
      type: "text"
      value: " (boolean)"
    type: "list"
    spread: false
    children:
      type: "listItem"
      spread: false
      children:
        type: "paragraph"
        summary: "As a couple of additions to ECMAScript 2015, Iteration protocols aren't new built-ins or syntax, but protocols. These protocols can be implemented by any object by following some conventions."
        rowIndex: 1
        shouldWrap: true
        children:
          type: "text"
          value: ": "
          type: "text"
          value: "Has the value "
          type: "inlineCode"
          value: "false"
          type: "text"
          value: " if the iterator was able to produce the next value in the sequence. (This is equivalent to not specifying the "
          type: "inlineCode"
          value: "done"
          type: "text"
          value: " property altogether.)"
        type: "paragraph"
        summary: "As a couple of additions to ECMAScript 2015, Iteration protocols aren't new built-ins or syntax, but protocols. These protocols can be implemented by any object by following some conventions."
        rowIndex: 1
        shouldWrap: true
        children:
          type: "text"
          value: "Has the value "
          type: "inlineCode"
          value: "true"
          type: "text"
          value: " if the iterator has completed its sequence. In this case, "
          type: "inlineCode"
          value: "value"
          type: "text"
          value: " optionally specifies the return value of the iterator."
  type: "listItem"
  spread: false
  children:
    type: "paragraph"
    children:
      type: "inlineCode"
      value: "value"
    type: "list"
    spread: false
    children:
      type: "listItem"
      spread: false
      children:
        type: "paragraph"
        children:
          type: "text"
          value: ": Any JavaScript value returned by the iterator. Can be omitted when "
          type: "inlineCode"
          value: "done"
          type: "text"
          value: " is "
          type: "inlineCode"
          value: "true"
          type: "text"
          value: ".",type: "paragraph"
summary: "As a couple of additions to ECMAScript 2015, Iteration protocols aren't new built-ins or syntax, but protocols. These protocols can be implemented by any object by following some conventions."
rowIndex: 1
shouldWrap: true
children:
  type: "text"
  value: "The "
  type: "inlineCode"
  value: "next()"
  type: "text"
  value: " method must always return an object with appropriate properties including "
  type: "inlineCode"
  value: "done"
  type: "text"
  value: " and "
  type: "inlineCode"
  value: "value"
  type: "text"
  value: ". If a non-object value gets returned (such as "
  type: "inlineCode"
  value: "false"
  type: "text"
  value: " or "
  type: "inlineCode"
  value: "undefined"
  type: "text"
  value: "), a {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}} ("
  type: "inlineCode"
  value: "\"iterator.next() returned a non-object value\""
  type: "text"
  value: ") will be thrown."
```
##### tr (61:3) => tableRow
```
type: "html"
value: "<td>\n  <p>\n    A function, with either zero arguments or one argument, that returns an\n    object with at least the following two properties. If the\n    <code>next()</code> method is called with one argument, that argument will\n    be available to the <code>next()</code> method being invoked.\n  </p>\n  <dl>\n    <dt><code>done</code> (boolean)</dt>\n    <dd>\n      <p>\n        Has the value <code>false</code> if the iterator was able to produce the\n        next value in the sequence. (This is equivalent to not specifying the\n        <code>done</code> property altogether.)\n      </p>\n      <p>\n        Has the value <code>true</code> if the iterator has completed its\n        sequence. In this case, <code>value</code> optionally specifies the\n        return value of the iterator.\n      </p>\n    </dd>\n    <dt><code>value</code></dt>\n    <dd>\n      Any JavaScript value returned by the iterator. Can be omitted when\n      <code>done</code> is <code>true</code>.\n    </dd>\n  </dl>\n  <p>\n    The <code>next()</code> method must always return an object with appropriate\n    properties including <code>done</code> and <code>value</code>. If a\n    non-object value gets returned (such as <code>false</code> or\n    <code>undefined</code>), a {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}} (<code\n      >\"iterator.next() returned a non-object value\"</code\n    >) will be thrown.\n  </p>\n</td>\n"
```
##### table.standard-table (53:1) => table
```
type: "html"
value: "<tr>\n  <td><code>next()</code></td>\n  <td>\n    <p>\n      A function, with either zero arguments or one argument, that returns an\n      object with at least the following two properties. If the\n      <code>next()</code> method is called with one argument, that argument will\n      be available to the <code>next()</code> method being invoked.\n    </p>\n    <dl>\n      <dt><code>done</code> (boolean)</dt>\n      <dd>\n        <p>\n          Has the value <code>false</code> if the iterator was able to produce\n          the next value in the sequence. (This is equivalent to not specifying\n          the <code>done</code> property altogether.)\n        </p>\n        <p>\n          Has the value <code>true</code> if the iterator has completed its\n          sequence. In this case, <code>value</code> optionally specifies the\n          return value of the iterator.\n        </p>\n      </dd>\n      <dt><code>value</code></dt>\n      <dd>\n        Any JavaScript value returned by the iterator. Can be omitted when\n        <code>done</code> is <code>true</code>.\n      </dd>\n    </dl>\n    <p>\n      The <code>next()</code> method must always return an object with\n      appropriate properties including <code>done</code> and <code>value</code>.\n      If a non-object value gets returned (such as <code>false</code> or\n      <code>undefined</code>), a {{anN4cmVmKCJUeXBlRXJyb3IiKQ==}} (<code\n        >\"iterator.next() returned a non-object value\"</code\n      >) will be thrown.\n    </p>\n  </td>\n</tr>\n"
```
### [/en-US/docs/Web/JavaScript/Reference/Operators/delete](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/delete)
### Missing conversion rules
- span.seoSummary (19:4)
### [/en-US/docs/Web/JavaScript/Reference/Operators/Exponentiation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Exponentiation)
### Missing conversion rules
- kbd (49:62)
### [/en-US/docs/Web/JavaScript/Reference/Operators/function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/function)
### Missing conversion rules
- u (74:39)
### [/en-US/docs/Web/JavaScript/Reference/Operators/in](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/in)
### Missing conversion rules
- span.seoSummary (14:4)
- span.short_text[lang="en"] (31:54)
### [/en-US/docs/Web/JavaScript/Reference/Operators/new.target](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new.target)
### Missing conversion rules
- p.summary (89:1)
### [/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence)
#### Invalid AST transformations
##### tr (58:9) => tableRow
```
type: "html"
value: "<td>Code</td>\n",type: "html"
value: "<td>Output</td>\n"
```
##### td (63:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "function echo(name, num) {     console.log(\"Evaluating the \" + name + \" side\");     return num; } // Notice the division operator (/) console.log(echo(\"left\", 6) / echo(\"right\", 2)); "
```
##### td (73:13) => tableCell
```
type: "code"
lang: "plain"
meta: ""
value: "Evaluating the left side Evaluating the right side 3 "
```
##### tr (62:9) => tableRow
```
type: "html"
value: "<td>\n  <pre class=\"brush: js\">\nfunction echo(name, num) {\n    console.log(\"Evaluating the \" + name + \" side\");\n    return num;\n}\n// Notice the division operator (/)\nconsole.log(echo(\"left\", 6) / echo(\"right\", 2));\n</pre\n  >\n</td>\n",type: "html"
value: "<td>\n  <pre class=\"brush: plain\">\nEvaluating the left side\nEvaluating the right side\n3\n</pre\n  >\n</td>\n"
```
##### td (82:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "function echo(name, num) {     console.log(\"Evaluating the \" + name + \" side\");     return num; } // Notice the exponentiation operator (**) console.log(echo(\"left\", 2) ** echo(\"right\", 3));"
```
##### td (91:13) => tableCell
```
type: "code"
lang: "plain"
meta: ""
value: "Evaluating the left side Evaluating the right side 8"
```
##### tr (81:9) => tableRow
```
type: "html"
value: "<td>\n  <pre class=\"brush: js\">\nfunction echo(name, num) {\n    console.log(\"Evaluating the \" + name + \" side\");\n    return num;\n}\n// Notice the exponentiation operator (**)\nconsole.log(echo(\"left\", 2) ** echo(\"right\", 3));</pre\n  >\n</td>\n",type: "html"
value: "<td>\n  <pre class=\"brush: plain\">\nEvaluating the left side\nEvaluating the right side\n8</pre\n  >\n</td>\n"
```
##### table.standard-table (56:1) => table
```
type: "html"
value: "<tr>\n  <td>Code</td>\n  <td>Output</td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <pre class=\"brush: js\">\nfunction echo(name, num) {\n    console.log(\"Evaluating the \" + name + \" side\");\n    return num;\n}\n// Notice the division operator (/)\nconsole.log(echo(\"left\", 6) / echo(\"right\", 2));\n</pre\n    >\n  </td>\n  <td>\n    <pre class=\"brush: plain\">\nEvaluating the left side\nEvaluating the right side\n3\n</pre\n    >\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <pre class=\"brush: js\">\nfunction echo(name, num) {\n    console.log(\"Evaluating the \" + name + \" side\");\n    return num;\n}\n// Notice the exponentiation operator (**)\nconsole.log(echo(\"left\", 2) ** echo(\"right\", 3));</pre\n    >\n  </td>\n  <td>\n    <pre class=\"brush: plain\">\nEvaluating the left side\nEvaluating the right side\n8</pre\n    >\n  </td>\n</tr>\n"
```
##### tr (109:9) => tableRow
```
type: "html"
value: "<td>Code</td>\n",type: "html"
value: "<td>Output</td>\n"
```
##### td (114:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "function echo(name, num) {     console.log(\"Evaluating the \" + name + \" side\");     return num; } // Notice the division operator (/) console.log(echo(\"left\", 6) / echo(\"middle\", 2) / echo(\"right\", 3)); "
```
##### td (124:13) => tableCell
```
type: "code"
lang: "plain"
meta: ""
value: "Evaluating the left side Evaluating the middle side Evaluating the right side 1 "
```
##### tr (113:9) => tableRow
```
type: "html"
value: "<td>\n  <pre class=\"brush: js\">\nfunction echo(name, num) {\n    console.log(\"Evaluating the \" + name + \" side\");\n    return num;\n}\n// Notice the division operator (/)\nconsole.log(echo(\"left\", 6) / echo(\"middle\", 2) / echo(\"right\", 3));\n</pre\n  >\n</td>\n",type: "html"
value: "<td>\n  <pre class=\"brush: plain\">\nEvaluating the left side\nEvaluating the middle side\nEvaluating the right side\n1\n</pre\n  >\n</td>\n"
```
##### td (134:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "function echo(name, num) {     console.log(\"Evaluating the \" + name + \" side\");     return num; } // Notice the exponentiation operator (**) console.log(echo(\"left\", 2) ** echo(\"middle\", 3) ** echo(\"right\", 2)); "
```
##### td (144:13) => tableCell
```
type: "code"
lang: "plain"
meta: ""
value: "Evaluating the left side Evaluating the middle side Evaluating the right side 512 "
```
##### tr (133:9) => tableRow
```
type: "html"
value: "<td>\n  <pre class=\"brush: js\">\nfunction echo(name, num) {\n    console.log(\"Evaluating the \" + name + \" side\");\n    return num;\n}\n// Notice the exponentiation operator (**)\nconsole.log(echo(\"left\", 2) ** echo(\"middle\", 3) ** echo(\"right\", 2));\n</pre\n  >\n</td>\n",type: "html"
value: "<td>\n  <pre class=\"brush: plain\">\nEvaluating the left side\nEvaluating the middle side\nEvaluating the right side\n512\n</pre\n  >\n</td>\n"
```
##### td (154:13) => tableCell
```
type: "code"
lang: "js"
meta: ""
value: "function echo(name, num) {     console.log(\"Evaluating the \" + name + \" side\");     return num; } // Notice the parentheses around the left and middle exponentiation console.log((echo(\"left\", 2) ** echo(\"middle\", 3)) ** echo(\"right\", 2));"
```
##### td (163:13) => tableCell
```
type: "code"
lang: "plain"
meta: ""
value: "Evaluating the left side Evaluating the middle side Evaluating the right side 64"
```
##### tr (153:9) => tableRow
```
type: "html"
value: "<td>\n  <pre class=\"brush: js\">\nfunction echo(name, num) {\n    console.log(\"Evaluating the \" + name + \" side\");\n    return num;\n}\n// Notice the parentheses around the left and middle exponentiation\nconsole.log((echo(\"left\", 2) ** echo(\"middle\", 3)) ** echo(\"right\", 2));</pre\n  >\n</td>\n",type: "html"
value: "<td>\n  <pre class=\"brush: plain\">\nEvaluating the left side\nEvaluating the middle side\nEvaluating the right side\n64</pre\n  >\n</td>\n"
```
##### table.standard-table (107:1) => table
```
type: "html"
value: "<tr>\n  <td>Code</td>\n  <td>Output</td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <pre class=\"brush: js\">\nfunction echo(name, num) {\n    console.log(\"Evaluating the \" + name + \" side\");\n    return num;\n}\n// Notice the division operator (/)\nconsole.log(echo(\"left\", 6) / echo(\"middle\", 2) / echo(\"right\", 3));\n</pre\n    >\n  </td>\n  <td>\n    <pre class=\"brush: plain\">\nEvaluating the left side\nEvaluating the middle side\nEvaluating the right side\n1\n</pre\n    >\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <pre class=\"brush: js\">\nfunction echo(name, num) {\n    console.log(\"Evaluating the \" + name + \" side\");\n    return num;\n}\n// Notice the exponentiation operator (**)\nconsole.log(echo(\"left\", 2) ** echo(\"middle\", 3) ** echo(\"right\", 2));\n</pre\n    >\n  </td>\n  <td>\n    <pre class=\"brush: plain\">\nEvaluating the left side\nEvaluating the middle side\nEvaluating the right side\n512\n</pre\n    >\n  </td>\n</tr>\n",type: "html"
value: "<tr>\n  <td>\n    <pre class=\"brush: js\">\nfunction echo(name, num) {\n    console.log(\"Evaluating the \" + name + \" side\");\n    return num;\n}\n// Notice the parentheses around the left and middle exponentiation\nconsole.log((echo(\"left\", 2) ** echo(\"middle\", 3)) ** echo(\"right\", 2));</pre\n    >\n  </td>\n  <td>\n    <pre class=\"brush: plain\">\nEvaluating the left side\nEvaluating the middle side\nEvaluating the right side\n64</pre\n    >\n  </td>\n</tr>\n"
```
### Missing conversion rules
- sub (22:7)
- sub (22:26)
- td (59:13)
- td (60:13)
- td (110:13)
- td (111:13)
- table.fullwidth-table (223:1)
### [/en-US/docs/Web/JavaScript/Reference/Statements/async_function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function)
### Missing conversion rules
- div.notecard.note (81:1)
### [/en-US/docs/Web/JavaScript/Reference/Statements/var](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var)
### Missing conversion rules
- dfn (43:28)
- dfn (148:38)
### [/en-US/docs/Web/JavaScript/Reference/Template_literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)
### Missing conversion rules
- dfn (49:12)
