
## Authentication VS Authorization
- Authentication is about making sure the user is who they say they are. You're proving your identity with something you have like a username and password.
- Authorization is the next step. Once a user's identity is confirmed, authorization decides what parts of the application they are allowed to use.

---

## CURL (http methods, URL, header, body)

</hr>

1. `fileName!:string` - Filename is not nullable.
2. `createdAt?: Date` - this prop is optional.
3. `const x=y??""` - is y is null/undefined then x = empty string, otherwise x=y.
4. `export type SearchParams { [key:string]=string}` - key is string & its value is also string

---

- MongoDB server => DataBase software.
- Mongoose => command line tool to intract MongoDB (Prisma is for pgSQL). Express connects to mongoDB using mongoose
- MongoDB Compass => GUI tool to intract MongoDB.
- MongoDB Atlas cloud based mongoDB service

---

Note : If we use any react hook in nextJS app, we have to declear it as "useClient"

Note : passing closeModel in props of react component to close a popUp
   
QUESTIONS(FEATURES)
1. How to implement drag and drop in my application?

---

# VSCode help
[ Relaod window in VSCode- (ctrl + p) then (>re) ]

[ git confing (for differnt emails- (install extension - git config) then (ctrl + e) then (set config) then (provide details i.e. username & email)]

---

To connect remote system(VM) - `ssh -i ./id-rsa ubuntu@10.143.111.202` => `ssh -i <path of key> <VMusername>@<vmIP>`

---

Redis uses *in memory (RAM)* data storage. Traditional DB uses Disk storahe (ssd || hdd)

Order => register(0.3ns), L1 cache(0.9ns),L2 cache(2.8ns),L3 cache(12.9ns), RAML1 cache(120ns), SSD(50-150 US), HDD(1-10ms)
It is used as => 
1. cache(ideal for fast access to temp. data)
2. use as database (sutable for real time processing and storage)
3. use as message broker (for real time messaging needs)

