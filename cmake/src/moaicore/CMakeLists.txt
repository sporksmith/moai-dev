moai_set_local_source_dir()

add_library(moaicore STATIC
    "${local_source_dir}/MOAIDeckRemapper.h"
    "${local_source_dir}/MOAIBox2DWeldJoint.h"
    "${local_source_dir}/MOAIGfxDevice.cpp"
    "${local_source_dir}/MOAIFrameBuffer.cpp"
    "${local_source_dir}/MOAIRenderMgr.h"
    "${local_source_dir}/MOAIFoo.cpp"
    "${local_source_dir}/MOAIGfxQuad2D.h"
    "${local_source_dir}/MOAIScriptDeck.cpp"
    "${local_source_dir}/MOAIRenderMgr.cpp"
    "${local_source_dir}/MOAILua.h"
    "${local_source_dir}/MOAIDraw.cpp"
    "${local_source_dir}/MOAITransform.cpp"
    "${local_source_dir}/MOAIBox2DPrismaticJoint.cpp"
    "${local_source_dir}/MOAIRenderable.h"
    "${local_source_dir}/MOAIParticleDistanceEmitter.h"
    "${local_source_dir}/MOAIKeyboardSensor.cpp"
    "${local_source_dir}/MOAITileDeck2D.cpp"
    "${local_source_dir}/MOAIParser.cpp"
    "${local_source_dir}/MOAIRtti.h"
    "${local_source_dir}/MOAIIndexBuffer.cpp"
    "${local_source_dir}/MOAIBox2DRopeJoint.h"
    "${local_source_dir}/MOAITextDesigner.h"
    "${local_source_dir}/MOAISerializerBase.h"
    "${local_source_dir}/MOAIPathTerrainDeck.h"
    "${local_source_dir}/MOAIAnim.cpp"
    "${local_source_dir}/MOAITransformBase.h"
    "${local_source_dir}/MOAIGlyphCacheBase.h"
    "${local_source_dir}/MOAIPartitionResultMgr.h"
    "${local_source_dir}/MOAIInputDevice.h"
    "${local_source_dir}/MOAICpDebugDraw.cpp"
    "${local_source_dir}/MOAILuaState.cpp"
    "${local_source_dir}/MOAIObject.h"
    "${local_source_dir}/MOAISurfaceSampler2D.cpp"
    "${local_source_dir}/MOAICompassSensor.h"
    "${local_source_dir}/MOAIBox2DWeldJoint.cpp"
    "${local_source_dir}/MOAIAnim.h"
    "${local_source_dir}/MOAIUrlMgrNaCl.cpp"
    "${local_source_dir}/MOAIScissorRect.h"
    "${local_source_dir}/MOAISerializer.cpp"
    "${local_source_dir}/MOAIHttpTaskNaCl.cpp"
    "${local_source_dir}/MOAIWheelSensor.h"
    "${local_source_dir}/MOAIGlyphCacheBase.cpp"
    "${local_source_dir}/MOAIParticleCallbackPlugin.h"
    "${local_source_dir}/MOAICpConstraint.cpp"
    "${local_source_dir}/MOAIBox2DArbiter.h"
    "${local_source_dir}/MOAILuaRuntime.cpp"
    "${local_source_dir}/MOAIStaticGlyphCache.cpp"
    "${local_source_dir}/MOAIDebugLines.cpp"
    "${local_source_dir}/MOAIMultiTexture.h"
    "${local_source_dir}/MOAIHttpTaskCurl.cpp"
    "${local_source_dir}/MOAIJsonParser.h"
    "${local_source_dir}/MOAIImage.h"
    "${local_source_dir}/MOAILayer2D.h"
    "${local_source_dir}/MOAICamera2D.cpp"
    "${local_source_dir}/MOAIAnimCurve.cpp"
    "${local_source_dir}/MOAICpSpace.cpp"
    "${local_source_dir}/MOAIParticleState.cpp"
    "${local_source_dir}/MOAIParticlePlugin.cpp"
    "${local_source_dir}/MOAIParticleTimedEmitter.cpp"
    "${local_source_dir}/MOAIBox2DRevoluteJoint.h"
    "${local_source_dir}/MOAIParticlePexPlugin.h"
    "${local_source_dir}/MOAIGlobals.h"
    "${local_source_dir}/MOAITexture.h"
    "${local_source_dir}/MOAIEnvironment.cpp"
    "${local_source_dir}/MOAIParticleForce.cpp"
    "${local_source_dir}/MOAIBox2DMouseJoint.cpp"
    "${local_source_dir}/MOAILocationSensor.h"
    "${local_source_dir}/MOAIMesh.cpp"
    "${local_source_dir}/MOAIFreeTypeFontReader.h"
    "${local_source_dir}/MOAIColor.h"
    "${local_source_dir}/MOAIJoystickSensor.cpp"
    "${local_source_dir}/MOAICameraFitter2D.h"
    "${local_source_dir}/MOAIParticleCallbackPlugin.cpp"
    "${local_source_dir}/MOAIBoundsDeck.h"
    "${local_source_dir}/MOAIFileSystem.cpp"
    "${local_source_dir}/MOAIDeck.h"
    "${local_source_dir}/MOAISim.cpp"
    "${local_source_dir}/MOAIGlyphCachePage.cpp"
    "${local_source_dir}/MOAIShader.h"
    "${local_source_dir}/MOAILuaStateHandle.cpp"
    "${local_source_dir}/MOAIBox2DDistanceJoint.h"
    "${local_source_dir}/MOAIGlyphSet.h"
    "${local_source_dir}/MOAIBox2DGearJoint.cpp"
    "${local_source_dir}/MOAIBox2DDebugDraw.cpp"
    "${local_source_dir}/MOAIGfxQuadListDeck2D.h"
    "${local_source_dir}/MOAIScriptNode.h"
    "${local_source_dir}/MOAIScriptNode.cpp"
    "${local_source_dir}/MOAIImageTexture.cpp"
    "${local_source_dir}/MOAIGfxQuadDeck2D.h"
    "${local_source_dir}/MOAITimer.h"
    "${local_source_dir}/MOAIParticleSystem.cpp"
    "${local_source_dir}/MOAIRenderable.cpp"
    "${local_source_dir}/MOAIUrlMgrCurl.h"
    "${local_source_dir}/MOAISurfaceSampler2D.h"
    "${local_source_dir}/MOAIBlocker.cpp"
    "${local_source_dir}/MOAIParticleState.h"
    "${local_source_dir}/MOAIPartitionLevel.cpp"
    "${local_source_dir}/MOAIHttpTaskNaCl.h"
    "${local_source_dir}/MOAITileFlags.h"
    "${local_source_dir}/MOAICoroutine.cpp"
    "${local_source_dir}/MOAIQuadBrush.cpp"
    "${local_source_dir}/MOAIPathGraph.h"
    "${local_source_dir}/MOAIGlyphCache.h"
    "${local_source_dir}/MOAIPathTerrainDeck.cpp"
    "${local_source_dir}/MOAIPartitionLevel.h"
    "${local_source_dir}/MOAIGridPathGraph.h"
    "${local_source_dir}/MOAIButtonSensor.cpp"
    "${local_source_dir}/MOAIPartitionResultBuffer.h"
    "${local_source_dir}/MOAIEaseDriver.h"
    "${local_source_dir}/MOAIShaderMgr.h"
    "${local_source_dir}/MOAIGlyphCachePage.h"
    "${local_source_dir}/MOAIButtonSensor.h"
    "${local_source_dir}/MOAIStretchPatch2D.cpp"
    "${local_source_dir}/MOAIBox2DRopeJoint.cpp"
    "${local_source_dir}/MOAILuaSharedPtr.h"
    "${local_source_dir}/MOAIFreeTypeFontReader.cpp"
    "${local_source_dir}/MOAIParticleSystem.h"
    "${local_source_dir}/MOAIFontReader.h"
    "${local_source_dir}/MOAICameraAnchor2D.cpp"
    "${local_source_dir}/MOAIParticlePlugin.h"
    "${local_source_dir}/MOAIProp2D.cpp"
    "${local_source_dir}/moaicore.h"
    "${local_source_dir}/MOAIInputDevice.cpp"
    "${local_source_dir}/MOAIBlendMode.h"
    "${local_source_dir}/MOAIBox2DJoint.cpp"
    "${local_source_dir}/MOAIImageTexture.h"
    "${local_source_dir}/MOAIVertexBuffer.cpp"
    "${local_source_dir}/MOAILayoutFrame.h"
    "${local_source_dir}/MOAITouchSensor.cpp"
    "${local_source_dir}/MOAITileDeck2D.h"
    "${local_source_dir}/pch.h"
    "${local_source_dir}/MOAIDraw.h"
    "${local_source_dir}/MOAIPathFinder.h"
    "${local_source_dir}/MOAIProp.h"
    "${local_source_dir}/MOAIBox2DBody.h"
    "${local_source_dir}/MOAIUrlMgrCurl.cpp"
    "${local_source_dir}/MOAILayer2D.cpp"
    "${local_source_dir}/MOAICanary.h"
    "${local_source_dir}/MOAILogMgr.cpp"
    "${local_source_dir}/MOAIEventSource.h"
    "${local_source_dir}/MOAIJoystickSensor.h"
    "${local_source_dir}/MOAIGfxQuadDeck2D.cpp"
    "${local_source_dir}/MOAIViewport.h"
    "${local_source_dir}/MOAIGfxResource.h"
    "${local_source_dir}/MOAIEventSource.cpp"
    "${local_source_dir}/MOAIBoundsDeck.cpp"
    "${local_source_dir}/MOAIColor.cpp"
    "${local_source_dir}/MOAICpSpace.h"
    "${local_source_dir}/MOAIGfxResource.cpp"
    "${local_source_dir}/MOAICameraFitter2D.cpp"
    "${local_source_dir}/MOAISurfaceDeck2D.h"
    "${local_source_dir}/MOAIBlocker.h"
    "${local_source_dir}/MOAICpShape.cpp"
    "${local_source_dir}/MOAICamera2D.h"
    "${local_source_dir}/MOAIStretchPatch2D.h"
    "${local_source_dir}/MOAIFont.h"
    "${local_source_dir}/MOAIGfxQuad2D.cpp"
    "${local_source_dir}/MOAISpanList.h"
    "${local_source_dir}/MOAIBox2DRevoluteJoint.cpp"
    "${local_source_dir}/MOAIShaderMgr.cpp"
    "${local_source_dir}/MOAIShader.cpp"
    "${local_source_dir}/MOAILayer.cpp"
    "${local_source_dir}/MOAICpBody.h"
    "${local_source_dir}/MOAIFooMgr.h"
    "${local_source_dir}/MOAIEaseType.h"
    "${local_source_dir}/MOAISharedPtr.h"
    "${local_source_dir}/MOAIParticleEmitter.cpp"
    "${local_source_dir}/MOAIImage-jpg.cpp"
    "${local_source_dir}/MOAICpConstraint.h"
    "${local_source_dir}/MOAIGrid.cpp"
    "${local_source_dir}/MOAILogMessages.h"
    "${local_source_dir}/MOAILuaState.h"
    "${local_source_dir}/MOAIBox2DMouseJoint.h"
    "${local_source_dir}/MOAIBox2DFrictionJoint.cpp"
    "${local_source_dir}/MOAIPartition.cpp"
    "${local_source_dir}/MOAINode.cpp"
    "${local_source_dir}/MOAIProp2D.h"
    "${local_source_dir}/MOAIGfxQuadListDeck2D.cpp"
    "${local_source_dir}/MOAITransform.h"
    "${local_source_dir}/MOAIPointerSensor.h"
    "${local_source_dir}/MOAIBlendMode.cpp"
    "${local_source_dir}/MOAIFooMgr.cpp"
    "${local_source_dir}/MOAIHttpTaskBase.h"
    "${local_source_dir}/MOAIGlyph.cpp"
    "${local_source_dir}/MOAILogMessages.cpp"
    "${local_source_dir}/MOAIIndexBuffer.h"
    "${local_source_dir}/MOAIParticleForce.h"
    "${local_source_dir}/MOAIParticleScript.cpp"
    "${local_source_dir}/MOAIActionMgr.h"
    "${local_source_dir}/MOAIBox2DGearJoint.h"
    "${local_source_dir}/MOAIGlobals.cpp"
    "${local_source_dir}/MOAICpShape.h"
    "${local_source_dir}/MOAIBox2DWheelJoint.h"
    "${local_source_dir}/MOAIParticleScript.h"
    "${local_source_dir}/MOAIParticleTimedEmitter.h"
    "${local_source_dir}/MOAICollisionShape.cpp"
    "${local_source_dir}/MOAIDataIOAction.h"
    "${local_source_dir}/MOAIGlyph.h"
    "${local_source_dir}/MOAIInputMgr.cpp"
    "${local_source_dir}/MOAIPartitionResultBuffer.cpp"
    "${local_source_dir}/MOAIBox2DWheelJoint.cpp"
    "${local_source_dir}/MOAILogMgr.h"
    "${local_source_dir}/MOAIFont.cpp"
    "${local_source_dir}/MOAIBox2DPulleyJoint.cpp"
    "${local_source_dir}/MOAIDebugLines.h"
    "${local_source_dir}/MOAIParticleEmitter.h"
    "${local_source_dir}/MOAIBox2DWorld.cpp"
    "${local_source_dir}/MOAILuaStateHandle.h"
    "${local_source_dir}/MOAIFileSystem.h"
    "${local_source_dir}/MOAILuaObject.h"
    "${local_source_dir}/MOAIPathGraph.cpp"
    "${local_source_dir}/MOAITimer.cpp"
    "${local_source_dir}/MOAIParticleDistanceEmitter.cpp"
    "${local_source_dir}/MOAISerializer.h"
    "${local_source_dir}/MOAICamera.h"
    "${local_source_dir}/MOAISerializerBase.cpp"
    "${local_source_dir}/MOAIVertexBuffer.h"
    "${local_source_dir}/MOAIBox2DArbiter.cpp"
    "${local_source_dir}/MOAITextureBase.cpp"
    "${local_source_dir}/MOAISensor.h"
    "${local_source_dir}/MOAIViewport.cpp"
    "${local_source_dir}/MOAITransformBase.cpp"
    "${local_source_dir}/MOAIImage.cpp"
    "${local_source_dir}/MOAIVertexFormat.cpp"
    "${local_source_dir}/MOAILuaRuntime.h"
    "${local_source_dir}/MOAIEaseType.cpp"
    "${local_source_dir}/MOAIHttpTaskCurl.h"
    "${local_source_dir}/MOAIGridSpace.cpp"
    "${local_source_dir}/MOAIInputMgr.h"
    "${local_source_dir}/MOAIParticle.h"
    "${local_source_dir}/MOAIGlyphSet.cpp"
    "${local_source_dir}/MOAIStaticGlyphCache.h"
    "${local_source_dir}/MOAIWheelSensor.cpp"
    "${local_source_dir}/MOAIBox2DBody.cpp"
    "${local_source_dir}/MOAIPartition.h"
    "${local_source_dir}/MOAICamera.cpp"
    "${local_source_dir}/MOAIBitmapFontReader.cpp"
    "${local_source_dir}/MOAIPvrHeader.h"
    "${local_source_dir}/MOAICpDebugDraw.h"
    "${local_source_dir}/MOAIVertexFormatMgr.cpp"
    "${local_source_dir}/MOAIAttrOp.h"
    "${local_source_dir}/MOAITextStyle.cpp"
    "${local_source_dir}/MOAIFoo.h"
    "${local_source_dir}/MOAIWeakPtr.h"
    "${local_source_dir}/MOAIDeserializer.cpp"
    "${local_source_dir}/MOAIBitmapFontReader.h"
    "${local_source_dir}/MOAIJsonParser.cpp"
    "${local_source_dir}/MOAISim.h"
    "${local_source_dir}/MOAICp.h"
    "${local_source_dir}/MOAINodeMgr.h"
    "${local_source_dir}/MOAILayer.h"
    "${local_source_dir}/MOAIFontReader.cpp"
    "${local_source_dir}/MOAINodeMgr.cpp"
    "${local_source_dir}/MOAITouchSensor.h"
    "${local_source_dir}/MOAIPathFinder.cpp"
    "${local_source_dir}/moaicore.cpp"
    "${local_source_dir}/MOAIBox2DWorld.h"
    "${local_source_dir}/MOAILuaObject-impl.h"
    "${local_source_dir}/MOAIGlyphCache.cpp"
    "${local_source_dir}/MOAIFrameBuffer.h"
    "${local_source_dir}/MOAITextBundle.h"
    "${local_source_dir}/MOAIMotionSensor.cpp"
    "${local_source_dir}/MOAIBox2DPrismaticJoint.h"
    "${local_source_dir}/MOAIMesh.h"
    "${local_source_dir}/MOAIDataBuffer.cpp"
    "${local_source_dir}/MOAIHttpTaskBase.cpp"
    "${local_source_dir}/MOAIObject.cpp"
    "${local_source_dir}/MOAITransform2D.h"
    "${local_source_dir}/MOAILuaRef.cpp"
    "${local_source_dir}/MOAIProp.cpp"
    "${local_source_dir}/MOAICpArbiter.cpp"
    "${local_source_dir}/MOAIMultiTexture.cpp"
    "${local_source_dir}/MOAILocationSensor.cpp"
    "${local_source_dir}/MOAIParticlePexPlugin.cpp"
    "${local_source_dir}/MOAICameraAnchor2D.h"
    "${local_source_dir}/MOAIMotionSensor.h"
    "${local_source_dir}/MOAIGfxDevice.h"
    "${local_source_dir}/MOAILuaState-impl.h"
    "${local_source_dir}/MOAIDeckRemapper.cpp"
    "${local_source_dir}/MOAIDataBuffer.h"
    "${local_source_dir}/MOAIBox2DJoint.h"
    "${local_source_dir}/MOAICpBody.cpp"
    "${local_source_dir}/MOAIDataIOAction.cpp"
    "${local_source_dir}/MOAITextStyler.cpp"
    "${local_source_dir}/MOAITexture.cpp"
    "${local_source_dir}/MOAIEnvironment.h"
    "${local_source_dir}/MOAIGridPathGraph.cpp"
    "${local_source_dir}/MOAIGridSpace.h"
    "${local_source_dir}/MOAIGrid.h"
    "${local_source_dir}/MOAIBox2DDebugDraw.h"
    "${local_source_dir}/MOAIQuadBrush.h"
    "${local_source_dir}/MOAIPartitionCell.cpp"
    "${local_source_dir}/MOAICoroutine.h"
    "${local_source_dir}/MOAIXmlParser.h"
    "${local_source_dir}/MOAIPointerSensor.cpp"
    "${local_source_dir}/MOAIBox2DPulleyJoint.h"
    "${local_source_dir}/shaders"
    "${local_source_dir}/shaders/MOAIDeck2DShader-vsh.h"
    "${local_source_dir}/shaders/MOAIDeck2DTexOnlyShader-vsh.h"
    "${local_source_dir}/shaders/MOAIFontShader-vsh.h"
    "${local_source_dir}/shaders/MOAIDeck2DShader-fsh.h"
    "${local_source_dir}/shaders/MOAILineShader-fsh.h"
    "${local_source_dir}/shaders/MOAIMeshShader-fsh.h"
    "${local_source_dir}/shaders/MOAIDeck2DTexOnlyShader-fsh.h"
    "${local_source_dir}/shaders/MOAIMeshShader-vsh.h"
    "${local_source_dir}/shaders/MOAIFontShader-fsh.h"
    "${local_source_dir}/shaders/MOAILineShader-vsh.h"
    "${local_source_dir}/MOAIScriptDeck.h"
    "${local_source_dir}/MOAIParser.h"
    "${local_source_dir}/MOAIDeck.cpp"
    "${local_source_dir}/MOAIKeyboardSensor.h"
    "${local_source_dir}/MOAIPartitionCell.h"
    "${local_source_dir}/MOAIEaseDriver.cpp"
    "${local_source_dir}/MOAIAnimCurve.h"
    "${local_source_dir}/MOAICanary.cpp"
    "${local_source_dir}/MOAITextDesigner.cpp"
    "${local_source_dir}/MOAICpArbiter.h"
    "${local_source_dir}/MOAICompassSensor.cpp"
    "${local_source_dir}/MOAICollisionShape.h"
    "${local_source_dir}/MOAIBox2DFrictionJoint.h"
    "${local_source_dir}/MOAIActionMgr.cpp"
    "${local_source_dir}/MOAITextBox.cpp"
    "${local_source_dir}/MOAICp.cpp"
    "${local_source_dir}/MOAINode.h"
    "${local_source_dir}/MOAITextBox.h"
    "${local_source_dir}/MOAITextStyle.h"
    "${local_source_dir}/MOAIXmlParser.cpp"
    "${local_source_dir}/MOAISurfaceDeck2D.cpp"
    "${local_source_dir}/MOAITileFlags.cpp"
    "${local_source_dir}/MOAILuaRef.h"
    "${local_source_dir}/MOAIDeserializer.h"
    "${local_source_dir}/MOAIAction.h"
    "${local_source_dir}/MOAIVertexFormatMgr.h"
    "${local_source_dir}/MOAIAction.cpp"
    "${local_source_dir}/moaicore-pch.cpp"
    "${local_source_dir}/MOAISensor.cpp"
    "${local_source_dir}/MOAIBox2DDistanceJoint.cpp"
    "${local_source_dir}/MOAITextStyler.h"
    "${local_source_dir}/MOAIBox2DFixture.h"
    "${local_source_dir}/MOAITransform2D.cpp"
    "${local_source_dir}/MOAIUrlMgrNaCl.h"
    "${local_source_dir}/MOAIRtti.cpp"
    "${local_source_dir}/MOAITextureBase.h"
    "${local_source_dir}/MOAILuaObject.cpp"
    "${local_source_dir}/MOAIScissorRect.cpp"
    "${local_source_dir}/MOAIPartitionResultMgr.cpp"
    "${local_source_dir}/MOAIImage-png.cpp"
    "${local_source_dir}/MOAIFont_bmfont.cpp"
    "${local_source_dir}/MOAITextBundle.cpp"
    "${local_source_dir}/MOAILayerBridge.cpp"
    "${local_source_dir}/MOAILayerBridge.h"
    "${local_source_dir}/MOAILayoutFrame.cpp"
    "${local_source_dir}/MOAIBox2DFixture.cpp"
    "${local_source_dir}/MOAIVertexFormat.h"
    "${local_source_dir}/MOAIAnimCurveBase.cpp"
    "${local_source_dir}/MOAIAnimCurveBase.h"
    "${local_source_dir}/MOAIAnimCurveQuat.cpp"
    "${local_source_dir}/MOAIAnimCurveQuat.h"
    "${local_source_dir}/MOAIAnimCurveVec.cpp"
    "${local_source_dir}/MOAIAnimCurveVec.h"
    "${local_source_dir}/MOAIDataBufferStream.cpp"
    "${local_source_dir}/MOAIDataBufferStream.h"
    "${local_source_dir}/MOAIFileStream.cpp"
    "${local_source_dir}/MOAIFileStream.h"
    "${local_source_dir}/MOAIGridDeck2D.cpp"
    "${local_source_dir}/MOAIGridDeck2D.h"
    "${local_source_dir}/MOAIMemStream.cpp"
    "${local_source_dir}/MOAIMemStream.h"
    "${local_source_dir}/MOAIStreamReader.cpp"
    "${local_source_dir}/MOAIStreamReader.h"
    "${local_source_dir}/MOAIStreamWriter.cpp"
    "${local_source_dir}/MOAIStreamWriter.h"
    "${local_source_dir}/MOAIStream.cpp"
    "${local_source_dir}/MOAIStream.h"
    "${local_source_dir}/MOAIHashWriter.cpp"
    "${local_source_dir}/MOAIHashWriter.h"
)

target_link_libraries(moaicore
    Box2D
    chipmunk
    tinyxml
    uslscore
    ${JPEG_LIBRARIES}
    ${PNG_LIBRARIES}
    ${CURL_LIBRARIES}
    ${FREETYPE_LIBRARIES}
)
