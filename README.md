# amazon-sumerian-concierge-booth
This is a sample concierge demo which builds off of the stock concierge demo provided by AWS with added functionality tailored for booth function demo.

## Setup Instructions
 1. Install the Sumerian Virtual Concierge according to https://docs.sumerian.amazonaws.com/articles/virtual-concierge/
   1. Create a new Sumerian scene and import the Sumerian Virtual Concierge via "Import Assets"
   2. Run the cloud formation script to create the Cognito user group. (Save the cognito group ID)
   3. Upload jsfeat face and main files to S3 and make them publically accessible. (Save their web links) 
   4. Create the LEX. (Save the LEX bot name and stage)
 2. Update the MainScript.js with the one here.
 3. Create a new DynamoDB table and store csv data in there.
 4. Update LEX bot with updated utterances provided in this repo.


