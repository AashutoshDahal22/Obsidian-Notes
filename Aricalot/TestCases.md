#work
## Reorder

- Cannot add order to the log which is not pinned

- Can add different order to the same log from different user

- When the log is unpinned from **user1** then from the **pinContexts**[] only the data related to the **user1** is remove order of other users is not removed or changed

- if the **myPin**[] has the **user1** and we try to send the data of **user2** it will say activity not pinned which is true since the id will not be found

- Sending empty `pinContexts[]` → should throw `ACTIVITY_ID_MISSING`

- Same user reorders the same log twice and it should overwrite adds the new order

- reorder with entityType that deosnt exists in the enum says not able to deserialize data 400 request error

- **Reorder a log that has both CASE and USER pinContexts** → update only CASE order, verify USER order is untouched and vice versa

- **Send a `contextId` that exists in `pinContexts[]` but with wrong `contextType`** → for example the contextId is correct but you send `contextType: "CASE"` when it's actually `"USER"` → throws `ACTIVITY_NOT_PINNED

- **Send `null` order value** → sends invlaid order id

- **Send `order: 0` or negative order** → sends invalid order id

## Bulk Permission Updte

- Added condition to make sure that the user doesn't have any permission