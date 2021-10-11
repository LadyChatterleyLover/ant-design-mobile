# Dropdown

<code src="./demos/demo1.tsx"></code>

# API

| Name      | Description                        | Type                          | Default |
| --------- | ---------------------------------- | ----------------------------- | ------- |
| activeKey | Active `Item` `key`                | `string`                      | -       |
| onChange  | Triggered when `activeKey` changes | `(activeKey?: string)=> void` | -       |

## Dropdown.Item

| Name        | Description                                            | Type        | Default |
| ----------- | ------------------------------------------------------ | ----------- | ------- |
| key         | The unique value                                       | `string`    | -       |
| title       | Title                                                  | `ReactNode` | -       |
| highlight   | Highlight                                              | `boolean`   | `false` |
| forceRender | Whether to render the content even if it is not active | `boolean`   | `false` |