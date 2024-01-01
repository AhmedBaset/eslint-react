[@eslint-react/tools](../README.md) / [Data](../modules/Data.md) / [Case](../modules/Data.Case.md) / Constructor

# Interface: Constructor\<A, Tag\>

[Data](../modules/Data.md).[Case](../modules/Data.Case.md).Constructor

**`Since`**

2.0.0

## Type parameters

| Name | Type |
| :------ | :------ |
| `A` | extends [`Case`](Data.Case-1.md) |
| `Tag` | extends keyof `A` = `never` |

## Callable

### Constructor

▸ **Constructor**(`args`): `A`

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | `Equals`\<`Omit`\<`A`, typeof [`symbol`](../modules/Equal.md#symbol) \| typeof `symbol` \| `Tag`\>, {}\> extends ``true`` ? `void` : \{ readonly [P in string \| number \| symbol as P extends typeof symbol \| typeof symbol \| Tag ? never : P]: A[P] } |

#### Returns

`A`
