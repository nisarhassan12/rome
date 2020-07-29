# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > cast > type-assertion`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/cast/type-assertion/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/cast/type-assertion/input.ts"
		end: Object {
			column: 0
			index: 12
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/cast/type-assertion/input.ts"
				end: Object {
					column: 11
					index: 11
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: TSTypeAssertion {
				loc: Object {
					filename: "typescript/cast/type-assertion/input.ts"
					end: Object {
						column: 10
						index: 10
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				typeAnnotation: TSNumberKeywordTypeAnnotation {
					loc: Object {
						filename: "typescript/cast/type-assertion/input.ts"
						end: Object {
							column: 7
							index: 7
							line: 1
						}
						start: Object {
							column: 1
							index: 1
							line: 1
						}
					}
				}
				expression: JSNumericLiteral {
					value: 1
					format: undefined
					loc: Object {
						filename: "typescript/cast/type-assertion/input.ts"
						end: Object {
							column: 10
							index: 10
							line: 1
						}
						start: Object {
							column: 9
							index: 9
							line: 1
						}
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```