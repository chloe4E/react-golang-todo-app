# I. In server folder
## a. Initialize Go app
go mod init github.com/chloe4e/go-react-application

## b. Install Fiber v2
go get -u github.com/gofiber/fiber/v2

# II. In root folder
## a. Create client app with Vite
yarn create vite client -- --template react-ts

# III. In client folder
## a. Install dependencies
yarn add @mantine/hooks @mantine/core swr @primer/octicons-react


Above is the general set-up.
After running these commands, we start with the server creation.