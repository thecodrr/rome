# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > declare-export > invalid-export-let`

```javascript
Program {
  comments: Array []
  corrupt: true
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 31
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: '`declare export let` is not supported. Use `declare export var` instead'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 14
          index: 14
          line: 1
        }
        start: Object {
          column: 15
          index: 15
          line: 1
        }
      }
    }
  ]
  body: Array [
    FlowDeclareExportDefault {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 14
          index: 14
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: StringLiteralTypeAnnotation {
        value: 'INVALID_PLACEHOLDER'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 14
            index: 14
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
      }
    }
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 30
          index: 30
          line: 1
        }
        start: Object {
          column: 15
          index: 15
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'let'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 30
            index: 30
            line: 1
          }
          start: Object {
            column: 15
            index: 15
            line: 1
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingIdentifier {
              name: 'foo'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 30
                  index: 30
                  line: 1
                }
                start: Object {
                  column: 19
                  index: 19
                  line: 1
                }
              }
              meta: PatternMeta {
                definite: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 30
                    index: 30
                    line: 1
                  }
                  start: Object {
                    column: 19
                    index: 19
                    line: 1
                  }
                }
                typeAnnotation: NumberKeywordTypeAnnotation {
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 30
                      index: 30
                      line: 1
                    }
                    start: Object {
                      column: 24
                      index: 24
                      line: 1
                    }
                  }
                }
              }
            }
            init: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 30
                index: 30
                line: 1
              }
              start: Object {
                column: 19
                index: 19
                line: 1
              }
            }
          }
        ]
      }
    }
  ]
}
```