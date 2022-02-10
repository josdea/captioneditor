# Caption Editor from Amazon Transcribe Output

- AWS Transcribe costs around $0.00050 cents per second of audio transcription. And it gives you 60 minutes a month free under their free tier. The output, however, is a large JSON (Javascript Object) with confidence intervals. This must be converted into a caption file in either the SRT or VTT format. This tool helps with this. 

## Steps to Use
1. Create an account and start a free year trial of [AWS](https://aws.amazon.com/)
2. Use the AWS transcribe tool. Here is a [getting started](https://aws.amazon.com/transcribe/getting-started/) guide. But the steps are basically you upload an audio or video to an S3 storage bucket and then select it from within AWS transcribe.
3. Wait 2-3 minutes for the transcription to happen.
4. Download the output file and open it in this caption editor to produce VTT or SRT files.
5. Once you load the file you can update either side of the editor.