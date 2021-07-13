# dekab-back
MVP of dekab project backend

## Request examples
/users GET [{name: "aaaa", id "1111", profilePicSmall: "piclink.img"}]

/push PUT [{link_address: "", type: "html", hints: {freeform: ""}}]
=> [{addres_id: "sdgwre"}]

/query POST {user_id: "", tags: {...}} => [{address_id, address}]
//TDOD redo as GET

/mark_as_read PATCH [{user_id: "1111", address_id: "124"}] 