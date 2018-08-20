## Post [/post/{id}]
A single Gist object.
The Gist resource is the central resource in the Gist Fox API.
It represents one paste - a single text note.

+ Parameters
  + id (string) ... ID of the post in the form of a hash.

+ Model

    + Body

      ```
      :[](../jsonFixtures/post.json)
      ```

### Retrieve a Single Gist [GET]

+ Response 200

  [Post]