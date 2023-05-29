# Mertsy SDK for iOS. 3D capturing sample.

The Mertsy SDK allows you to integrate 3D/360 product imaging and capturing functionality into your application. It consists of several modules. Some modules may not be available to you, check your license restrictions.

<img src="https://cappasity.com/wp-content/uploads/2022/07/MertsySDK-scaled.jpg" alt="Mertsy SDK" style="width:1000px;"/>

Instruction:

1. Download Mertsy SDK.
2. Copy Mertsy.xcframework to "PLACE_XC_FRAMEWORK_HERE" folder.
3. Set up your Development Team in the "Signing and Capabilities" tab.
4. To initialize the SDK, set your Mertsy SDK Access Token to token property.

```swift

class AppDelegate: UIResponder, UIApplicationDelegate {
    
    func application(_ application: UIApplication, didFinishLaunchingWithOptions launchOptions: [UIApplication.LaunchOptionsKey: Any]?) -> Bool {
        MertsySDK.shared.token = "YOUR TOKEN HERE"
        return true
    }
}
```

5. Launch the app. Select a shooting mode (Indoor, Cars and Vehicles or Panorama) and follow the instructions.
6. When the capture is complete, the ID of the new model will be set to the lastCreatedModelID property.
7. Select 'View model' mode.

# Contact us

SDK access: support@cappasity.com
Website - https://cappasity.com/contact/

Copyright (c) 2023 Cappasity Inc. All rights reserved.

Neither the name of Cappasity Inc., nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


              
