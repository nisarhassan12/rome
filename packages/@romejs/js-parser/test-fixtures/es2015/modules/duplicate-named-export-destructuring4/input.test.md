# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > modules > duplicate-named-export-destructuring4`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 52
      line: 3
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ExportLocalDeclaration {
      exportKind: 'value'
      specifiers: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 24
          index: 24
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: FunctionDeclaration {
        id: BindingIdentifier {
          name: 'foo'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 19
              index: 19
              line: 1
            }
            start: Object {
              column: 16
              index: 16
              line: 1
            }
          }
        }
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 24
            index: 24
            line: 1
          }
          start: Object {
            column: 7
            index: 7
            line: 1
          }
        }
        body: BlockStatement {
          body: Array []
          directives: Array []
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 24
              index: 24
              line: 1
            }
            start: Object {
              column: 22
              index: 22
              line: 1
            }
          }
        }
        head: FunctionHead {
          async: false
          generator: false
          hasHoistedVars: false
          params: Array []
          predicate: undefined
          rest: undefined
          returnType: undefined
          thisType: undefined
          typeParameters: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 22
              index: 22
              line: 1
            }
            start: Object {
              column: 19
              index: 19
              line: 1
            }
          }
        }
      }
    }
    EmptyStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 25
          index: 25
          line: 1
        }
        start: Object {
          column: 24
          index: 24
          line: 1
        }
      }
    }
    ExportLocalDeclaration {
      exportKind: 'value'
      specifiers: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 25
          index: 51
          line: 2
        }
        start: Object {
          column: 0
          index: 26
          line: 2
        }
      }
      declaration: VariableDeclarationStatement {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 25
            index: 51
            line: 2
          }
          start: Object {
            column: 7
            index: 33
            line: 2
          }
        }
        declaration: VariableDeclaration {
          kind: 'const'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 25
              index: 51
              line: 2
            }
            start: Object {
              column: 7
              index: 33
              line: 2
            }
          }
          declarations: Array [
            VariableDeclarator {
              id: BindingArrayPattern {
                rest: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 18
                    index: 44
                    line: 2
                  }
                  start: Object {
                    column: 13
                    index: 39
                    line: 2
                  }
                }
                elements: Array [
                  BindingIdentifier {
                    name: 'foo'
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 17
                        index: 43
                        line: 2
                      }
                      start: Object {
                        column: 14
                        index: 40
                        line: 2
                      }
                    }
                    meta: PatternMeta {
                      optional: undefined
                      typeAnnotation: undefined
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 17
                          index: 43
                          line: 2
                        }
                        start: Object {
                          column: 14
                          index: 40
                          line: 2
                        }
                      }
                    }
                  }
                ]
              }
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 24
                  index: 50
                  line: 2
                }
                start: Object {
                  column: 13
                  index: 39
                  line: 2
                }
              }
              init: ReferenceIdentifier {
                name: 'bar'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 24
                    index: 50
                    line: 2
                  }
                  start: Object {
                    column: 21
                    index: 47
                    line: 2
                  }
                }
              }
            }
          ]
        }
      }
    }
  ]
}
```